# edu-neo-candy-tela

Tela-flavoured Neo-Candy icon theme — colourful icons that pair with the [Tela](https://github.com/vinceliuice/Tela-icon-theme) design family. Part of the `~/EDU/` Neo-Candy series.

## What's in this repo

- `usr/share/icons/` — the icon theme assets.
- `setup.sh`, `up.sh` — standard EDU bash scaffold.

## Sibling variants

- [edu-neo-candy-arc](https://github.com/erikdubois/edu-neo-candy-arc)
- [edu-neo-candy-arc-mint-grey](https://github.com/erikdubois/edu-neo-candy-arc-mint-grey)
- [edu-neo-candy-arc-mint-red](https://github.com/erikdubois/edu-neo-candy-arc-mint-red)
- [edu-neo-candy-qogir](https://github.com/erikdubois/edu-neo-candy-qogir)

## Installation

### From `nemesis_repo` (recommended)

```ini
[nemesis_repo]
SigLevel = Never
Server = https://erikdubois.github.io/$repo/$arch
```

```bash
sudo pacman -Syu
sudo pacman -S edu-neo-candy-tela
```

### Manual

```bash
git clone https://github.com/erikdubois/edu-neo-candy-tela.git
cd edu-neo-candy-tela
sudo cp -r usr/share/icons/. /usr/share/icons/
sudo gtk-update-icon-cache -f /usr/share/icons/<theme-folder>
```

### Activate

```bash
gsettings set org.gnome.desktop.interface icon-theme "<theme-folder-name>"
```

## Websites

Information : https://erikdubois.be

## Social Media

Youtube : https://www.youtube.com/erikdubois

## License

See [LICENSE](./LICENSE).
