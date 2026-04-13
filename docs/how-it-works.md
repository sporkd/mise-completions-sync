# How It Works

`mise-completions-sync` follows a simple process to generate shell completions:

1. **Discover installed tools** - Gets list of installed tools via `mise ls --installed --json`
2. **Look up registry entries** - Each tool is matched against the built-in registry
3. **Generate completions** - Runs the tool's completion command (e.g., `kubectl completion zsh`)
4. **Save output** - Writes completions to `~/.local/share/mise-completions/<shell>/`

## Registry

The registry (`registry.toml`) contains patterns for generating completions. Each entry specifies:

- The tool name (matching mise's tool name)
- A format pattern for the completion command
- Which shells are supported

Example entry:

```toml
[tools.kubectl]
format = "{bin} completion {shell}"
shells = ["zsh", "bash", "fish"]
```

The format pattern supports these placeholders:

- `{bin}` - The tool's binary path
- `{shell}` - The target shell (zsh, bash, fish)

## Output Location

Completions are saved to `$XDG_DATA_HOME/mise-completions/<shell>/` (defaults to `~/.local/share/mise-completions/<shell>/`).

Each tool gets its own completion file named `_<tool>` (for zsh) or `<tool>.bash`/`<tool>.fish` for other shells.

Additionally, you can override the output directory for one or more shells by setting the `MISE_COMPLETIONS_SYNC_{SHELL}_DIR` environment variable (e.g., `MISE_COMPLETIONS_SYNC_ZSH_DIR`). This is useful if you prefer to use your shell's standard completion directories. For example, the following would sync (and clean) all zsh competions to `~/.local/share/zsh/site-functions/` instead of `$XDG_DATA_HOME/mise-completions/zsh/`

```shell
export MISE_COMPLETIONS_SYNC_ZSH_DIR="$XDG_DATA_HOME/zsh/site-functions"

mise-completions-sync

mise-completions-sync clean
```

Note: Target directories will be created they don't already exist.
