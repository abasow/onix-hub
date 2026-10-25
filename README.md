# onix-hub

An image and PKG tool for the PS5. It runs on the console as a payload and is controlled through a web GUI you open from a phone or PC browser.

## Features
- **Build:** create PKG / FFPKG / exFAT images from a game folder
- **Unpack:** extract an image into a folder
- **Add patch:** patch `.ffpfsc`, `.ffpkg`, `.ffpfs` and `.exfat` images in place
- **File manager & image manager:** browse the console's files and look inside images without unpacking them. Create folders, rename, delete, add files or folders, or extract them from the image. A `.pkg` is read-only (browse and extract only).
- Install queue
- Interface languages: Azerbaijani, Turkish, Russian, English
- Access protected by a pairing code (shown on the PS5 screen)

## Download
Get the latest `onixhub.elf` from the [Releases](../../releases) page.

## Usage
1. Send `onixhub.elf` to your PS5 with your payload sender (port 9021).
2. Open the address shown on the PS5 screen (`http://<PS5-IP>:<port>`) in a browser on your phone or PC.
3. Enter the 6-digit pairing code shown on the PS5.

## Requirements
- A jailbroken PS5 with an ELF loader running
- Use only with your own legally obtained copies

## Disclaimer
Provided as is, without warranty. Use at your own risk.

---
by **Abasow**
