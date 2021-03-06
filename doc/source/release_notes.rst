Release notes
=============

0.4 (01.09.2014)
----------------
- add position argument with restricted values
- rename executables wm_reader/wm_writer to wm-reader/wm-writer
- make destination format same as input (by default)
- write watermark only to specified bands
- read only specified bands

0.3 (01.07.2014)
----------------
- read/write multiple watermarks (like in chain)
- custom help for methods
- added arg --version
- switch to latest pillow (2.4.0)
- lot of new tests

0.2 (01.06.2014)
----------------

- possibility to set watermark's position (topleft, center, ...)
- executables part of pip installation
- new arguments quiet/verbose, suffix and position
- each method can now have it's own extra command line arguments
- create destination directory if it does not exists
- use tox to test this library
- BaseMethod class for easier development of custom methods
- requirements split for users and developers (no need to install libs you do not need)


0.1.1 (01.05.2014)
------------------

- fix crash when processing unsupported file format/mode
- improved installation process
- improved Python3 support
- various small fixes


0.1 (23.04.2014)
----------------

- very first version of Watermarks
- support for lsb reading/writing
- support for writing visible watermarks
- support for user defined watermark methods
- bunch of analyze tools
- runs with Python 2.6, 2.7, 3.x
