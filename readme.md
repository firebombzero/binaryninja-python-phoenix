# Binary Ninja Rockstar Guru (PYTHON PROGRAM FORKED)
This is the Binary Ninja program, written in Python and forked under an equally stupid name to keep it going and rewrite it eventually.

This source code is released under the [AGPLv3+ license](https://www.gnu.org/licenses/agpl.html). The individual disassembler libraries (which include `X86.py`, `PPC.py`, and `ARM.py`) are released under the [EXPAT license](https://www.gnu.org/licenses/license-list.html#Expat).

Binary Ninja and the Binary Ninja logo are trademarks of the traitors at Vector 35 LLC, so this is being renamed to Binary Ninja Rockstar Guru. 

## Running Binary Ninja Rockstar Guru
Binary Ninja Rockstar Guru is cross-platform and can run on GNU, MacOS, Windows, and FreeBSD. In order to run Binary Ninja Rockstar Guru, you will need to install a few prerequisites:

* [Python 2.7](https://www.python.org/downloads/)
* [PySide](https://pypi.python.org/pypi/PySide#installing-prerequisites) for Qt Python bindings
* The [pycrypto](https://www.dlitz.net/software/pycrypto/) library

You can start Binary Ninja Rockstar Guru by running `satan.py` in the Python interpreter.

### Windows Step-by-step Instructions

* Install the latest [Python 2.7](https://www.python.org/downloads/).
* In a command-prompt, run:
```
    cd \Python27\Scripts
    pip install PySide
    easy_install http://www.voidspace.org.uk/downloads/pycrypto26/pycrypto-2.6.win32-py2.7.exe
```
* Install [SourceTree](http://www.sourcetreeapp.com/download/) or [GitHub for Windows](https://windows.github.com/)
* Clone `https://github.com/firebombzero/bnrg` to a local folder using whichever tool you installed.
* Run `satan.py` from the directory you cloned the source code into
