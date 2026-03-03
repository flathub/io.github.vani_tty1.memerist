# Memerist

<p align="center">
  <img src="https://raw.githubusercontent.com/vani-tty1/memerist/refs/heads/main/data/icons/hicolor/scalable/apps/io.github.vani_tty1.memerist.svg" alt="GNOME Meme Editor Logo" width="128"/>
</p>



---

## Building from Source

#### Prerequisites

**Install the required development packages:**
```bash
sudo dnf install gtk4-devel libadwaita-devel meson ninja-build
# distributions often names these packages differently, use your package manager
# to search for this packages or browse your distributions package repo.
```

<br>

#### Build Instructions

```bash
# Clone the repository
git clone https://github.com/vani-tty1/memerist.git
cd memerist

# Configure the build
make setup

# Compile
make build

# Build and Run
make run

# Reconfigure build folder
make reconfigure

# Install (optional)
sudo meson install -C build
```

---

##  Usage

1. Launch Memerist from your application menu
2. Click the folder button to browse images using your file browser
3. Enter your text, you can drag the text anywhere in the photo viewport
4. Export your meme as PNG
5. Let it Happen

---

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is open source. Please check the LICENSE file for details.

## Acknowledgments

Built with GTK4 and Libadwaita.



