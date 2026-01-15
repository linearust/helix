# Helix Config

Personal configuration for [Helix](https://helix-editor.com/).

## Installation

```sh
rm -rf ~/.config/helix  # remove existing config if any
git clone https://github.com/linearust/helix.git ~/.config/helix
```

## Requirements

The configured theme (`github_dark_high_contrast`) requires true color support. Add this to your `~/.bashrc`:

```sh
export COLORTERM=truecolor
```

## Files

- `config.toml` — Editor settings (theme, line numbers, auto-save)
- `languages.toml` — Language-specific settings (Rust with clippy, auto-format)
