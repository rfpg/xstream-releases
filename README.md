# XStream Audio Plugin - Release Binaries

This repository contains official release builds of the XStream granular synthesis audio plugin.

## Download Latest Release

Visit the [Releases](https://github.com/rfpg/xstream-releases/releases/latest) page to download the latest version.

## Available Platforms

- **macOS**: Universal binary (Intel + Apple Silicon)
  - Formats: AU, VST3, Standalone
- **Windows**: 64-bit
  - Formats: VST3, Standalone
- **Linux**: 64-bit
  - Formats: VST3, Standalone

## Getting Started

### Installation

**macOS (Recommended):**
1. Download the DMG file from [Releases](https://github.com/rfpg/xstream-releases/releases/latest)
2. Open the DMG and double-click the PKG installer
3. Follow the installation wizard
4. Restart your DAW and rescan plugins

**Windows:**
1. Download and extract the ZIP file
2. Copy `XStream.vst3` to: `C:\Program Files\Common Files\VST3\`
3. Copy `XStream.exe` to your preferred location
4. Restart your DAW and rescan plugins

**Linux:**
1. Download and extract: `tar -xzf xstream-linux.tar.gz`
2. Copy `XStream.vst3` to: `~/.vst3/`
3. Copy the `XStream` executable to your preferred location
4. Restart your DAW and rescan plugins

### Quick Start Guide

XStream has two modes for different creative workflows:

**Looper Mode** - Traditional Granular Synthesis
- Load an audio sample or record live input
- Adjust grain size, density, and playback position
- Perfect for creating evolving textures, pads, and drones
- Use the position controls to scrub through your sample

**PolySynth Mode** - Polyphonic Granular Synthesis
- Play your samples chromatically across a MIDI keyboard
- Each key triggers independent granular voices
- Create playable granular instruments
- Full velocity sensitivity and polyphonic support

### Basic Workflow

1. **Load a Sample**: Drag and drop an audio file or use the file browser
2. **Choose Your Mode**: Toggle between Looper Mode and PolySynth Mode
3. **Adjust Grain Parameters**:
   - Grain Size: Controls the length of each grain
   - Grain Density: How many grains play simultaneously
   - Position: Where in the sample grains are captured from
4. **Shape the Sound**:
   - Use the envelope controls to shape grain attack/release
   - Adjust pitch and time independently
5. **Add Effects**: Apply built-in effects for further sound design

## Documentation

For full documentation, feature roadmap, and support, visit:
https://rfpg.github.io/xstream/

## Support

- **Email**: beta@deltasoundlabs.com
- **Issues**: [Report a bug](https://github.com/rfpg/xstream-releases/issues)

## About XStream

XStream is a versatile granular synthesis platform with three planned development phases:

- **Phase 1** (Current): Looper Mode and PolySynth Mode
- **Phase 2** (In Development): 3D spatial granular synthesis with panel wall rendering
- **Phase 3** (Future): Polyphonic distortion synthesis

---

© 2024 Delta Sound Labs. All rights reserved.
