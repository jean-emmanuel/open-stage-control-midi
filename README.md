## open-stage-control-midi

*This is an experimental feature*

The requirements for enabling MIDI support in Open Stage Control can hard to install, especially under Windows. This is an attempt to provide ready-to-use binaries that Open Stage Control can use without needing any thing else installed.

Binaries are built using [pyinstaller](https://www.pyinstaller.org/), cross-compiling is done with [docker-pyinstaller](https://github.com/cdrx/docker-pyinstaller)

## Supported platforms

- Linux: 64bit, 32bit
- Windows: 64bit, 32bit

## Usage

Download the appropriate binary file for you system and add this in Open Stage Control's midi option:

`path=path/to/executable`
