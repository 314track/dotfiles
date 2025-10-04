# dotfiles

Some dotfiles managed with GNU Stow

## Preperation

```bash
cd ~ && git clone https://github.com/314track/dotfiles.git
```

## Install GNU Stow

```bash
apt install stow
```

## Run GNU Stow

```bash
cd ~/dotfiles && stow .
```

## Remove symlinks in ~

```bash
cd ~/dotfiles && stow -D .
```
