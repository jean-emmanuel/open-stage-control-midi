## open-stage-control-midi


The requirements for enabling MIDI support in Open Stage Control can be hard to install, especially under Windows. This is an attempt to provide ready-to-use binaries that Open Stage Control can use without needing any thing else installed.

Binaries are built using [pyinstaller](https://www.pyinstaller.org/), cross-compiling is done with Travis-CI.

## Supported platforms

- Linux 64bit
- Windows 64bit
- OSX 64bit

## Usage

Download the binary for your system in `open-stage-control-linux/resources/app/server/`, make it executable and create a `osc-midi.json` file with `true` in it.

```bash
ARCH=linux
cd open-stage-control-linux/resources/app/server/
wget https://github.com/jean-emmanuel/open-stage-control-midi/releases/latest/download/osc-midi-$ARCH
chmod +x osc-midi-$ARCH && echo "true" > osc-midi.json
```
