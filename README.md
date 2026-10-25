# dotfiles

My personal Linux configuration files: AwesomeWM, Zsh with Powerlevel10k, and the
rest of my terminal and desktop setup. I keep them here to version my environment
and get a fresh machine up and running quickly.

## What's inside

- `.config/awesome/` — AwesomeWM window manager configuration (Lua)
- `.zshrc` / `.p10k.zsh` — Zsh shell and Powerlevel10k prompt
- `powerlevel10k/` — prompt theme
- `wallpapers/` — wallpapers used by the setup

## Usage

These are personal configs, so treat them as a reference rather than a drop-in
install. Back up your own files first, then copy what you need:

```bash
# Example: shell config
cp .zshrc ~/.zshrc
cp .p10k.zsh ~/.p10k.zsh

# Example: AwesomeWM config
cp -r .config/awesome ~/.config/
```

Reload your shell (`exec zsh`) or restart AwesomeWM to apply the changes.
