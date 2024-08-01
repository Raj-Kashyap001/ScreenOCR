# ScreenOCR For Linux
A simple script to capture a screenshot, perform OCR on it, and copy the text to the clipboard.

## Features

* Captures a screenshot using Flameshot
* Performs Optical Character Recognition (OCR) on the screenshot using Tesseract
* Copies the recognized text to the clipboard

## Installation

1. **Install dependencies** based on your system:

   * **For Ubuntu/Debian**:
     ```bash
     sudo apt-get install flameshot tesseract-ocr xclip
     ```

   * **For Arch Linux**:
     ```bash
     sudo pacman -S flameshot tesseract xclip
     ```

   * **For Fedora/CentOS/RHEL**:
     ```bash
     sudo dnf install flameshot tesseract xclip
     ```

   * **For NixOS**:
     ```bash
     nix-env -iA nixos.flameshot nixos.tesseract nixos.xclip
     ```


2. **Make the script executable** with `chmod +x screenocr`

3. **Copy the script** to a location in your system's PATH (e.g., `/usr/local/bin/`)

## Usage

1. **Run `screenocr`** in your terminal
2. **Select the region** of the screen you want to capture
3. The script will **perform OCR** on the screenshot and **copy the text** to the clipboard
4. You will **receive a notification** upon success or failure

## Tip: Bind to a Keyboard Shortcut
For easy access, **bind the `screenocr` command** to a keyboard shortcut. For example, in GNOME, you can use the "Keyboard" settings to bind `screenocr` to a key combination like `Ctrl + Shift + O`.

## Configuration

Edit the script as you like...

## Contributing

Contributions are welcome! If you'd like to improve the script or add new features, please submit a pull request.


## Disclaimer

This program is provided "as is" without warranty of any kind, either expressed or implied. In no event shall the authors or copyright holders be liable for any claim, damages or other liability, whether in an action of contract, tort or otherwise, arising from, out of or in connection with the software or the use or other dealings in the software.


## License

ScreenOCR is released under the MIT License.


