# mise-completions-sync

Automatically sync shell completions for tools managed by [mise](https://mise.jdx.dev/).

## Installation

```bash
mise use -g github:alltuner/mise-completions-sync
```

Or download from [releases](https://github.com/alltuner/mise-completions-sync/releases), or build from source with `cargo install --git https://github.com/alltuner/mise-completions-sync`.

## Shell Setup

Add the completions directory to your shell config.

**ZSH** - add to `~/.zshrc` before `compinit`:
```zsh
fpath=(${XDG_DATA_HOME:-$HOME/.local/share}/mise-completions/zsh $fpath)
```

**Bash** - add to `~/.bashrc`:
```bash
for f in ${XDG_DATA_HOME:-$HOME/.local/share}/mise-completions/bash/*; do
  [[ -f "$f" ]] && source "$f"
done
```

**Fish** - add to `~/.config/fish/config.fish`:
```fish
set -gx fish_complete_path $fish_complete_path ~/.local/share/mise-completions/fish
```

## Usage

```bash
# Sync completions for all installed tools
mise-completions-sync

# Sync only for specific shell
mise-completions-sync --shell zsh

# Sync specific tools
mise-completions-sync kubectl helm

# List supported tools
mise-completions-sync list

# Clean up completions for uninstalled tools
mise-completions-sync clean
```

## Updating

To update to the latest version:

```bash
mise upgrade github:alltuner/mise-completions-sync
```

Or to pin a specific version:

```bash
mise use -g github:alltuner/mise-completions-sync@0.3.0
```

## Automatic Sync

Set up a mise hook to sync completions when tools are installed:

```bash
mkdir -p ~/.config/mise && cat >> ~/.config/mise/config.toml << 'EOF'

[hooks]
postinstall = "mise-completions-sync"
EOF
```

## Custom Output Dirs

By default, completions are synced to `$XDG_DATA_HOME/mise-completions/<shell>`. However, you can override the output directories using environment variables:

```shell
# Override default base output directory
export MISE_COMPLETIONS_SYNC_HOME="$XDG_DATA_HOME/custom-vendor-completions"
```

Or you can override output targets on a per-shell basis (these take precedence over the base override above):

```shell
# Bash completions to standard bash location
export MISE_COMPLETIONS_SYNC_BASH_DIR="$XDG_DATA_HOME/bash-completion/completions"

# ZSH completions to standard zsh location
export MISE_COMPLETIONS_SYNC_ZSH_DIR="$XDG_DATA_HOME/zsh/site-functions"

# Fish completions to standard fish locations
export MISE_COMPLETIONS_SYNC_FISH_DIR="$HOME/fish/completions"
# (or)
export MISE_COMPLETIONS_SYNC_FISH_DIR="$XDG_DATA_HOME/fish/vendor_completions.d"
```

Note: Target directories will be created if they don't already exist. Don't forget to update your shell setup above.

## Documentation

See the [full documentation](https://alltuner.github.io/mise-completions-sync/) for supported tools and more details.

## License

MIT

---

Built at [All Tuner Labs](https://alltuner.com) by [David Poblador i Garcia](https://davidpoblador.com)
