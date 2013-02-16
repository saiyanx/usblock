=======
USBLock
=======

Copyright (C) 2013  Sven Steinbauer http://www.unlogic.co.uk

USBlock is a Python script that will lock and unlock your linux box using any 
old USB storage device as a key.

** NOTE **
V0.1 only works on Linux. OS X and Windows will have to wait a little.

Known Issues
============

* I've had some devices not mount on external USB ports (like on a Mac keyboard
or hub). DBus does not register the device insertion and so USBLock cannot
lock or unlock your machine. Try a different memory stick or USB port.

* On linux you need dbus installed. `pip install dbus-python` doesn't work, so 
you may have to install it via your system's package manager or from source.

Thanks for the patches
======================

Joel Semar, Natan L

