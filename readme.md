<div align='center'>

<h2>HyprSettings
</h2>

<img src='hyprsettingsicon.png' width='200' height='200'>

**I have forked this repo in order to preserve the package, as it's been very helpful, still usable and at risk of being lost to the void**

An unofficial GUI for configuring Hyprland, built with GTK4 and Rust. 🚀🦀<br>
Comes with a custom [hyprparser](https://github.com/nnyyxxxx/hyprparser) for Hyprland's configuration file. (Rust btw) 🦀

BUILD USING CARGO, AND ADD TO ROFI VIA 'MAIN MENU' FLATPAK
git clone //github.com/GlassPuddle/hyprsettings
cd hyprsettings/
cargo build

## Preview
![Preview](.github/preview.png)

</div>

## Installation


### Arch Linux

Install the preferred package with:
```bash
git clone //github.com/GlassPuddle/hyprsettings
cd hyprsettings/
cargo build
```


## Building from source
1. Install Rust (preferably `rustup`) through your distro's package or [the official script](https://www.rust-lang.org/tools/install)
2. Install `git`, `pango` and `gtk4`
3. Clone this repository:
`git clone https://github.com/GlassPuddle/hyprsettings/edit/main/readme.md && cd hyprgui`
4. Compile the app with `cargo build --release` or run it directly with `cargo run --release`


## Credits:
- [Nyx](https://github.com/nnyyxxxx) - Implementing the parser, rest of the GUI, and maintaining the project
- [Adam](https://github.com/adamperkowski) - Implementing the base GUI, maintaining the AUR packages and the project alongside Nyx
- [Vaxry](https://github.com/vaxerski) - Hyprland
- [rust-gtk](https://github.com/gtk-rs/gtk4-rs) - The GTK4 library
- [Hyprland](https://github.com/hyprwm/Hyprland) - The window manager

<h6 align='center'>Copyright (C) 2024 HyprUtils<h6>
