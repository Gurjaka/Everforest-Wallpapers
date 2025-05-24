<div align="center">

<img alt="Everforest Icon" src="./everforest.svg" width="180px"/>

# <samp>Everforest Wallpapers</samp>

![GitHub Repo stars](https://img.shields.io/github/stars/Gurjaka/Everforest-Wallpapers?style=for-the-badge\&labelColor=2b3339\&color=a7c080) ![GitHub last commit](https://img.shields.io/github/last-commit/Gurjaka/Everforest-Wallpapers?style=for-the-badge\&labelColor=2b3339\&color=a7c080) ![GitHub repo size](https://img.shields.io/github/repo-size/Gurjaka/Everforest-Wallpapers?style=for-the-badge\&labelColor=2b3339\&color=a7c080)

### A soothing collection of wallpapers inspired by the warm and earthy tones of the Everforest palette, made to bring a calm, nature-blended aesthetic to your desktop. 🌲🍃

</div>

## Why You'll Love It ✨

* **Warm & Calming Vibe**: Earthy and soft visuals that don’t strain your eyes. 🌿
* **Everforest Harmony**: Tailored for setups using the Everforest color scheme. 🍂
* **Screen-Ready Quality**: All wallpapers are high-res and look sharp on any monitor. 🖼️
* **Simple Integration**: Easily works with dotfiles and home manager configs. ⚙️

## Installation 🛠️

Getting Everforest Wallpapers on your system is simple:

1. **Clone the repository**:

```bash
git clone https://github.com/Gurjaka/Everforest-Wallpapers.git
```

### OR

2. **Use [nix flakes](https://wiki.nixos.org/wiki/Flakes)**:

2.1 Add this to your `flake.nix`:

```nix
inputs = {
  everforest-wallpapers.url = "github:Gurjaka/Everforest-Wallpapers";
  ...
}
```

2.2 Then symlink with Home Manager:

```nix
{
  inputs,
  pkgs,
  ...
}: {
  home.file = {
    "path/to/dir" = {
      source = inputs.everforest-wallpapers.packages."${pkgs.system}".default;
      recursive = true;
    };
  };
}
```

Browse the wallpapers, pick your favorite, and set the vibe. 🍵

## Setting It Up 🔧

Compatible with any desktop. To set a wallpaper with `feh`:

```bash
feh --bg-scale /path/to/wallpaper.jpg
```

## Contribution 🤝

Got a cozy Everforest-themed wallpaper you made? Fork, push, and PR it in. Always happy to expand the forest. 🌳

## License 📜

This project is licensed under the [MIT License](LICENSE). 🐾

---
