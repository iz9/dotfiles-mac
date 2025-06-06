# Dotfiles

Personal dotfiles managed with [dotbot](https://github.com/anishathalye/dotbot).

## Backup

To backup current configurations:
```bash
./install_dotbot.sh backup
```

## Restore

To restore configurations on a new system:
```bash
./install_dotbot.sh restore
```

## Structure
# .
# ├── config/                     # Application configurations
# │   ├── wezterm/               # WezTerm configuration
# │   ├── nvim/                  # Neovim configuration
# │   └── starship/             # Starship prompt configuration
# ├── git/                       # Git configuration
# ├── zsh/                       # Zsh configuration
# ├── ssh/                       # SSH configuration
# ├── install                    # Dotbot installation script
# └── install.conf.yaml          # Dotbot configuration
