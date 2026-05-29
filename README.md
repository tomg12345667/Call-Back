# FreePBX 8 Second Callback Service

Simple callback system for FreePBX/Asterisk using `.call` files.

Features:
- Automatic 8-second callback
- WAV playback before disconnect
- WAV playback after callback answer
- WebGUI for manual callbacks
- Uses native Asterisk `.call` files

## Install

```bash
git clone https://github.com/YOURNAME/fpbx-callback.git
cd fpbx-callback
chmod +x install.sh
sudo ./install.sh
