![Slow motion](demo/slow-motion.gif)

"Appear 3" is a KWin effect that animates appearing of windows.

## Installation

### Arch Linux

For Arch Linux [kwin-effects-appear3](https://aur.archlinux.org/packages/kwin-effects-appear3/)
is available in the AUR.

### Fedora

```sh
sudo dnf copr enable zzag/kwin-effects
sudo dnf refresh
sudo dnf install kwin-effects-appear3
```

### From source

```sh
git clone https://github.com/zzag/kwin-effects-appear3.git
cd kwin-effects-appear3
mkdir build && cd build
cmake ..
make -jN
sudo make install
```
