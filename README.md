# ✏️ Scriber 

Typography layout, style and animation toolkit in TouchDesigner

#### :floppy_disk: TouchDesigner 2023.11760 (Windows)
#### :floppy_disk: version 0.5.108
#### :floppy_disk: requires [Tweener](https://derivative.ca/community-post/asset/tweening-tweener-python-based-solution/65629) by Jason Latta

## 📖 Overview

Scriber enhances TouchDesigner's typography capabilities by providing per-character text transformations and animations. It aims to facilitate rapid iteration of type for motion graphics within TD.

## 🌟 Key Features

- Per-character kerning and animation
- Multi-line text support
- Animation preset system with per letter/word/line options
- DAT input compatibility
- Customizable animation parameters for intro and outro effects
- Camera positioning and width adjustment
- **Multi-font support** (a feature currently lacking in the standard textCOMP)

## 🚀 Installation

To install, drag and drop the tox from the `release/` folder into your network, or open up the toe, which includes a renderTOP setup.

## 🔧 Usage

1. Set your text in the "Text" field under the Type tab.
2. Adjust animation settings in the Anim tab:
   - Set Cue Anim, Anim In, and Anim Out parameters
   - Customize Intro and Outro durations, easing, and other properties
3. Fine-tune typography settings in the Type tab:
   - Adjust Camera Width and Position
   - Set Justify and Vertical Align options
   - Modify Font Size, Position, and Rotation
4. Use the preset system to save and load animation configurations

## 📝 Current Status

- Basic kerning implemented
- DAT inputs supported
- Multi-line text handling
- Improved animation preset system

## 🚧 Planned Features

- Position/rotation on 2D/3D paths ("Type on a Path")
- Potential 3D texture or spritesheet support for glyphs

## 🤝 Contributing

Open an issue, submit a PR, or send an email to rosco@tec.design.