# python-OTP-encryption
Some encryption algorithms based on the One Time Pad, written in python and tkinter.

OTP is a python program that allows you to encrypt/decrypt ASCII text using the One Time Pad system as well as generate random keys, generate checksums and check files against them. The keys and encrypted files are formatted in the classical way that spies used to use when they did this by hand back in the day (blocks of 5 characters and 3 spaces in between)

OTP.py is a command line tool, OTP-GUI.py is a tkinter GUI program.

bitwise XOR uses the same principle as OTP but it works with byte data not just with ASCII text, that means anything can be encrypted with it, images, movies, songs, etc.

bitwise_XOR_GUI.exe is a windows executable made with pyinstaller.

The interesting thing about this type of encryption is that despite it's extreme simplicity it has perfect secrecy, and although this comes with some bad consequences for usability, nowadays data is so cheap that most of it's setbacks are kind of irrelevant.
