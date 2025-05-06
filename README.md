# BalloonHistory (History of tooltips)

The BalloonHistory add-on allows you to Enable automatic registration of tooltips, as well as view registered tooltips in a separate dialog box.

### Key combination:

* NVDA+Shift+F11: Tooltip Logger Switch.
* NVDA+Control+F11: Open tooltip history.
* NVDA+Alt+F11: Clear tooltip history.
* NVDA+Windows+F11: Toggle the sound on new tooltips.

You can change the keyboard shortcut in тАЬinput gesturesтАЭ, in the тАЬTooltip historyтАЭ category.

### Settings:

The add-on's settings are located in the following path:
NVDA Menu, Submenu Options, Settings, тАЬTooltip HistoryтАЭ panel.

The тАЬTooltip HistoryтАЭ panel contains the following functions.

* Maximum number of tooltips to save. The default value is 25. (You can specify a minimum value of 1 and a maximum value of 1000).
* The number of tooltips to display in the history window. The default value is 10. (You can specify a minimum value of 1 and a maximum value of 1000).
* Enable sound for new tooltips when NVDA starts. Default value (Unchecked).
* Enable registration of tooltips when NVDA starts. Default value (Checked).
* Automatically clear the history of tooltips when NVDA starts. Default value (Unchecked).

### Example of registered tooltips:

Registered tooltips at shortcuts on the desktop.

After clicking on a shortcut:

* NVDA+Control+F11: Open the history of tooltips.

Note: If the tooltip history has been cleared or no tooltips have been registered yet, opening the history window will display a message that there is no tooltip history.

If tooltips have been registered, a dialog box will open, with a counter at the top showing the number of tooltips displayed, such as тАЬ85 tooltips shownтАЭ.

Below that will be a list in the following form:

1 month ago
Name: This computer
Tooltip: Displays disks and other devices connected to this computer.

1 months ago
Name: NVDA
Tooltip: Location: nvda_slave (C:\Program Files (x86)\NVDA)


### Cue recorder switch:

Immediately after the add-on is installed, the hint recorder will be enabled. You can disable the automatic start of the tooltip recorder in the add-on settings.
In addition, you can always turn the tooltip recorder on and off using the following keyboard shortcut:

* NVDA+Shift+F11: Tooltip recorder switch.

### Sound on new tooltips:

If this feature is enabled, you will hear a short Beep to notify you that a tooltip has been registered.
By default, this feature is disabled. If necessary, this feature can be enabled in the add-on settings, then when NVIDIA starts up, this feature will be enabled, or this feature can be turned on and off at any time using the keyboard shortcut:

* NVDA+Windows+F11: Toggle the sound of new tooltips.

### Clears the history of tooltips:

In the add-on settings, you can enable or disable the automatic tooltip history clearing feature. This feature is enabled by default.
If you need to keep the history of pop-up tooltips for a long time, then turn off the auto-cleaning option every time you start NVDA.
Note: To save logged tooltips for a long time, it is better to increase the number of tooltips saved and displayed in each field you can type or select any number from 1 and up to 1000.
If you need to manually clear the entire history of cues quickly, use the keyboard shortcut:

* NVDA+Alt+F11: Clear tooltip history.

### Change Log:

### Version 25.01.12.

* Compatible with NVDA API 2025.1.
* Added тАЬTooltip HistoryтАЭ category to input gestures.
* Added three more shortcuts with keyboard shortcuts for other functions to the shortcut for opening a dialog box to view tooltip history.
* Added a panel for add-on settings.
* Improved the dialog box for viewing hints.
* Added a function for automatic clearing of hints history and for manual clearing.
* Added a function to enable and disable tooltip logger from shortcut or through settings.
* Added a function to turn on and off the sound when registering a new tooltip using a shortcut or via settings.
* Compiled detailed help for the add-on.

### Version 1.1.

This is the latest version compatible with NVDA 2019.2 and older.
The add-on was abandoned by the developer.

