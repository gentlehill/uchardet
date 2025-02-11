# uchardet for Windows(x64) ignore dll version.
- Universal Charset Detector.

## Description
uchardet is an encoding and language detector library, which takes a sequence of bytes in an unknown character encoding without any additional information, and attempts to determine the encoding of the text.

* Returned encoding names are [iconv](https://www.gnu.org/software/libiconv/)-compatible.
* Returned language codes are ISO 639-1.

uchardet started as a C language binding of the original C++ implementation of the universal charset detection library by Mozilla. Since this far-away time, it can now detect more charsets, and much more reliably than the original implementation. Moreover it also work as a very good language detector, while still staying reasonably fast.

## Original Author
  Authors: BYVoid, Jehan
  Bug Report: [https://gitlab.freedesktop.org/uchardet/uchardet/-/issues](https://gitlab.freedesktop.org/uchardet/uchardet/-/issues)

## Usage
### Command Line

```
uchardet Command Line Tool
Version 0.0.8

Authors: BYVoid, Jehan
Bug Report: https://bugs.freedesktop.org/enter_bug.cgi?product=uchardet

Usage:
 uchardet [Options] [File]...

Options:
 -v, --version         Print version and build information.
 -h, --help            Print this help.
 ``` 
## Download.

[uchardet for Windows(x64) ignore dll version](https://github.com/gentlehill/uchardet/archive/refs/heads/main.zip "uchardet for Windows(x64) ignore dll version")

## Changelog

| Date       | Ver   | Log      | OS                    | Compiler           |
| :--------- | :---- | :------- | :-------------------- | :----------------- |
| 2025-02-10 | 0.0.8 | Compiled | Win11 24H2, 26100.3037| MSVC 2022, 17.12.4 |


## Licenses
Same license as the original author.

[https://gitlab.freedesktop.org/uchardet/uchardet](https://gitlab.freedesktop.org/uchardet/uchardet)
