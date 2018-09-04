# Windows Registry
### Disable screen saver
__Step 1__: Open Registry Editor. To do so, type Regedit in Start menu or taskbar search box and then press Enter key. Registry Editor can also be launched by typing Regedit in Run command box and pressing Enter key.

__Step 2__: In the Registry Editor, navigate to the following key:

HKEY_CURRENT_USER\Control Panel\Desktop

__Step 3__: On the right-side, look for the entry named ScreenSaveActive, double-click on it, and set the value to 1 (one) to enable screen saver and make it 0 (zero) to disable.
