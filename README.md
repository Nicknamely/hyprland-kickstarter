# Hyprland-KickStarter

## Overview
This project provides a modular, easy-to-navigate configuration for Hyprland, inspired by LazyVim’s approach to Neovim. The goal is to create a clean, functional setup that users can easily customize and expand upon.

## Why Modular?
A modular setup allows users to pick and choose which features to enable, making it easy to maintain and share configurations. Additionally, it simplifies the process of replacing or integrating someone else's configuration for specific categories, ensuring a more personalized and adaptable experience.
## Project Structure
```
.
├── core
│   ├── animations.conf
│   ├── binds.conf
│   ├── decoration.conf
│   ├── device.conf
│   ├── dwindle.conf
│   ├── environment.conf
│   ├── general.conf
│   ├── gestures.conf
│   ├── input.conf
│   ├── master.conf
│   ├── misc.conf
│   ├── monitor.conf -> ../extra/monitors/profile1.conf
│   └── workspaces.conf
├── extra
│   ├── monitors
│   │   ├── profile1.conf
│   │   └── profile2.conf
│   ├── plugins.conf
│   ├── rules
│   │   ├── 0-universal.conf
│   │   └── kitty.conf
│   ├── scripts
│   └── workspaces
├── hypridle.conf
├── hyprland.conf
├── hyprlock.conf
├── hyprpaper.conf
└── README.md
```


## Getting Started

## Future Plans
- Enhance the default configuration while maintaining minimalism.
- Supply non-executable scripts to assist with initial ricing (e.g., screenshotting with grim and slurp).
- Offer scripts for quick setup.
- Include troubleshooting tips and common fixes.
- Provide comprehensive comments to help with configuration (partially explaining stuff) but encourage reading the wiki.

## Contributing
Feel free to open issues, suggest improvements, or submit pull requests.

## License


