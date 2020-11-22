
# Horus

_The Godlike tool which views other people's systems_

## Background

_Why was this tool created and what purpose does it have?_

Web browsers and the Hyper-Text Transfer Protocol (HTTP) have let
humans communicate and visualize text documents in astounding new ways.

Originally your web browser viewed plain text which was owned by remote systems. You could then
read this text as if it were a book; there were some headers and italics and bold text and normal text.
The most complicated part of this was a "link" - fancy text which sent you to another remote system, or
a different part of the same system.

Skip ahead a few years and your browser forwarded non-plain-text data to non-web-browser programs like
[Java applets](https://en.wikipedia.org/wiki/Java_applet) or [Adobe](https://en.wikipedia.org/wiki/Adobe_Flash_Player) or [any of the other "Internet OS" systems](https://en.wikipedia.org/wiki/Internet_OS). You could then watch videos as if a DVD or Cassette Tape had been taken from a remote system, sent to your system, and displayed using some applications that were also taken from a remote system and sent to your system. Along the way sections of your system would obey rules sent alongside the video, for the purposes of displaying videos.

Concerns were raised over this "non-plain-text" data and the possiblity of ...


**TODO Finish writing the history without becoming complicated or political**.


## Distributon

See the (releases)[#Todo_link_goes_here] page for standalone binaries for "the big 3" operating systems:

 - [`horus-win64.exe`](#TODO_link): `PE32+` binary for Windows 10, 64-bit. This is a fancy wrapper around 64-bit `x86` code that calls `win32` code that you purchased from Microsoft.
 - [`horus-linux64`](#Todo_link): `ELF` binary for Linux, 64-bit. This is a fancy wrapper around 64-bit `x86` code that calls `libc` code (just like `win32` code) as well as using `x86` instructions to call kernel code directly (unique to monolithic kernels like Linux).
 - [`horus-macos64`](#Todo_link): `mach-o` binary for MacOS. This is currently a wrapper around 64-bit `x86` code that calls... we're not sure actually. MacOS has been pretty vague about it's executables and their formats.

TODO see [Comparison of executable file formats](https://en.wikipedia.org/wiki/Comparison_of_executable_file_formats)
and support as many as possible incl. icons.

## Usage

_Once you have a binary that can be run as `horus`_

```
horus [/path/to/file]
```

TODO documentation, TODO documentation, TODO documentation

## Development

_Oh good, you can clone the git repo. What next? How does this directory of code turn into a distributable file?_


TODO documentation, TODO documentation, TODO documentation

```
python build.py [todo args of some sort]
```

## Theory

_TODO get political in this section_


How should the world react to having a universal tool like `horus`? What does this mean
for new people, users, businesses, and governments?


