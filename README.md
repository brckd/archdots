# dotfiles

[![license](https://custom-icon-badges.demolab.com/github/license/brckd/dotfiles?logo=law)](LICENSE.md)

Dotfiles for Hyprland on Arch btw.

![dotfiles-github](https://github.com/brckd/dotfiles/assets/92804487/e9b36a07-1fdd-4512-9336-ecb3cd4a6bd2)

## Dependencies

| component | software                                                             | install                                                                                           |
| --------- | -------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- |
| os        | [Arch Linux](https://archlinux.org)                                  | [guide](https://wiki.archlinux.org/title/Installation_guide)                                      |
| wm        | [Hyprland](https://hyprland.org)                                     | [guide](https://wiki.hyprland.org/Getting-Started/Installation/)                                  |
| shell     | [Zsh](https://wiki.archlinux.org/title/Zsh)                          | `pacman -S zsh`                                                                                   |
| theme     | [Oh My ZSH!](https://ohmyz.sh)                                       | `sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"` |
| term      | [kitty](https://sw.kovidgoyal.net/kitty)                             | `pacman -S kitty`                                                                                 |
| editor    | [Neovim](https://neovim.io)                                          | `pacman -S neovim`                                                                                |
| theme     | [NvChad](https://nvchad.com)                                         | `git clone https://github.com/NvChad/NvChad ~/.config/nvim --depth 1 && nvim`                     |
| wallp     | [Hyprpaper](https://github.com/hyprwm/hyprpaper)                     | `pacman -S hyprpaper`                                                                             |
| colors    | [Pywal](https://github.com/dylanaraps/pywal)                         | `pacman -S python-pywal`                                                                          |
| notifs    | [Dunst](https://wiki.archlinux.org/title/Dunst)                      | `pacman -S dunst`                                                                                 |
| auth      | [polkit-kde-agent](https://invent.kde.org/plasma/polkit-kde-agent-1) | `pacman -S polkit-kde-agent`                                                                      |
| stats     | [rxfetch](https://github.com/Mangeshrex/rxfetch)                     | `yay -S rxfetch ttf-material-design-icons`                                                        |

## Usage

### Install

Install the [dependencies](#dependencies) listed above.

### Configure

Copy the config folders to their respective destination.

```zsh
cp -r hypr/ .config/
```
