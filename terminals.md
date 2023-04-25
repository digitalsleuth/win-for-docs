---
description: Use of Linux-emulated terminals on Windows
---

# Terminals

### Cygwin

Website: https://cygwin.com\
Description: Linux Terminal Emulator for Windows\
Author: https://cygwin.com/faq.html#faq.what.who\
License: GNU General Public License (GPL) (https://cygwin.com/licensing.html)\
Version: 3.4.6\
Notes: Retcode is set to '2' for success because the Cygwin installer (even though on Windows) attempts to search for /etc/setup/setup.rc or /etc/setup/installed.db and fails with retcode 2. This causes Saltstack to read an ERROR and result: False, even though the pkg state returns 'install success'.

### MobaXterm

Website: https://mobaxterm.mobatek.net\
Description: Enhanced Terminal for Windows\
Author: Mobatek (https://www.mobatek.net/aboutus.html)\
License: https://mobaxterm.mobatek.net/license.html\
<<<<<<< HEAD
Version: 23.0\
=======
Version: 22.2\
>>>>>>> 8983ec754f25e76a01add446f2bf6a953fdc0f34
Notes: Home Edition

### Windows Terminal

Website: https://github.com/microsoft/terminal\
Description: Terminal Emulator\
Author: Microsoft\
License: MIT License (https://github.com/microsoft/terminal/blob/main/LICENSE)\
<<<<<<< HEAD
Version: 1.16.(10261|10262).0\
Notes: Version depends on Windows OS version
=======
Version: 1.15.3465.0\
Notes:&#x20;
>>>>>>> 8983ec754f25e76a01add446f2bf6a953fdc0f34

### WSL Setup

Website: https://microsoft.com\
Description: Windows Subsystem for Linux setup\
Author: Microsoft\
License: EULA\
Version: 1.2.5.0\
Notes: Includes an Ubuntu 20.04 machine with SIFT and REMnux installed
