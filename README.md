# Dev environment Setup / Dotfiles

## Installation

```bash
mkdir ~/code
```

```bash
cd ~/code
```

```bash
git clone git@github.com:sameerkhanna/dotfiles.git
```

Setup submodules for vim plugins
```bash
git submodule init
```

Get fresh copy
```bash
git submodule update --init
```

Install everything via brew/pip
```bash
./.brew
```

Install dotfiles to ~/
```bash
./bootstrap.sh
```
## Thanks to…
[Mathias's Dotfiles](https://github.com/mathiasbynens/dotfiles)
