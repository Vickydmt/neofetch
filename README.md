
# Custom Neofetch Configuration

A customized Neofetch config file that gives your terminal a cool aesthetic touch and detailed system information with unique icons and dynamic image support (optimized for the **Kitty** terminal emulator).

---

## ✨ Features

- 🖼️ Dynamic background image display from a custom image directory.
- 🎨 Beautiful color-coded box layout using Unicode icons.
- 🧠 Intelligent image selection logic:
  - Rotates images to avoid repetition.
  - Resizes images based on terminal width and count.
- 💻 Displays rich system info:
  - Distro, CPU, Memory, Kernel, Shell, DE, WM, GPU, Disk, Fonts, and even 🎵 Now Playing music!
- ⚙️ Optimized for the `kitty` terminal emulator.
- ⌛ Sleep-based delay logic for better terminal count detection.

---

## 📁 Image Handling

- Directory: `~/.config/neofetch/images`
- Supports: `.jpg`, `.png`, `.jpeg`, `.gif`, `.bmp`
- Cache file to track recently used images: `~/.config/neofetch/last_images.txt`

Ensure that you have created "images" folder and add at least 5 images in the directory to enable dynamic rotation.

---

## 🛠️ Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Vickydmt/neofetch.git
````

2. Copy the config:

   ```bash
   cp neofetch/config.conf ~/.config/neofetch/config.conf
   ```

3. Add some images to:

   ```bash
   ~/.config/neofetch/images
   ```

4. Run Neofetch:

   ```bash
   neofetch
   ```

---

## 🔧 Terminal Support

> This setup is optimized for **Kitty**. You can modify the terminal count logic by changing `pgrep -c kitty` to your terminal (e.g., `alacritty`, `wezterm`, etc.).

---

## 🧪 Preview

```bash
                 zerotwo@zerotwo-rogstrixg531gd 
                 ┌──────────────────────────────────────┐ 
                   : ZeroTwo Linux x86_64 
                   : Intel i5-9300H (8) @ 4.100GHz 
                   : 2437MiB / 7787MiB 
                   : 6.14.7-arch2-1 
                   : 3 hours, 3 mins 
                   : zsh 5.9 
                   : Hyprland 
                   : Tela-circle-pink [GTK2/3] 
                   : kitty 
                 └─────────────────────         ┘ 
```

*(Note: Icons and output vary based on your actual system)*

---

## 🧠 Credits

* Based on [Neofetch](https://github.com/dylanaraps/neofetch) by Dylan Araps.
* Custom config by vickydmt
