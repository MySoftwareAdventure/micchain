# MicChain

Run your microphone through your own VST3 plugins (denoiser, compressor, EQ, de-esser...) and use the processed sound in any app - speech-to-text, Discord, OBS, calls.

**Download and install guide:** https://mysoftwareadventure.github.io/micchain/

## Features
- Your own plugin chain: add any VST3 plugin, reorder, switch on/off, double-click to open
- Monitor: hear exactly what other apps hear while you tweak
- Presets, with automatic switching when a chosen program is running
- Shortcuts: Ctrl+Alt+1-9 switches presets
- Runs in the tray and can start with Windows

## Requirements
- Windows 10 / 11 (64-bit)
- [VB-Cable](https://vb-audio.com/Cable/) (free virtual audio cable)
- VST3 plugins of your choice

## Building from source
1. Install Python 3 for Windows.
2. Double-click `build.bat`. It installs the build tools and creates `dist\MicChain\MicChain.exe`.
3. Optional: with [Inno Setup 6](https://jrsoftware.org/isdl.php) installed, it also creates `installer\MicChain-Setup.exe`.

## License
GPL-3.0. Built with [pedalboard](https://github.com/spotify/pedalboard) by Spotify (GPL-3.0).

Made by [My Software Adventure](https://youtube.com/@mysoftwareadventure).
