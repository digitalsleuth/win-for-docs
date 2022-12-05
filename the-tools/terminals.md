# Terminals

### Name: Cygwin

Website: https://cygwin.com\
Description: Linux Terminal Emulator for Windows\
Author: https://cygwin.com/faq.html#faq.what.who\
License: GNU General Public License (GPL) (https://cygwin.com/licensing.html)\
Version: 3.3.6\
Notes: Retcode is set to '2' for success because the Cygwin installer (even though on Windows) attempts to search for /etc/setup/setup.rc or /etc/setup/installed.db and fails with retcode 2. This causes Saltstack to read an ERROR and result: False, even though the pkg state returns 'install success'.

### Name: MobaXterm

Website: https://mobaxterm.mobatek.net\
Description: Enhanced Terminal for Windows\
Author: Mobatek (https://www.mobatek.net/aboutus.html)\
License: https://mobaxterm.mobatek.net/license.html\
Version: 22.0\
Notes: Home Edition

### Name: Windows Terminal

Website: https://github.com/microsoft/terminal\
Description: Terminal Emulator\
Author: Microsoft\
License: MIT License (https://github.com/microsoft/terminal/blob/main/LICENSE)\
Version: 1.11.3471.0\
Notes:

### Name: WSL Setup

Website: https://microsoft.com\
Description: Windows Subsystem for Linux setup\
Author: Microsoft\
License: EULA\
Version: 0.0\
Notes: NOT CURRENTLY INSTALLED - PENDING UPDATES FROM MICROSOFT
