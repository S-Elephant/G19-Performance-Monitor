===============================================================================
About
===============================================================================
Performance Monitor is open source PC monitoring software written in C#. You
can download it from SourceForge.

===============================================================================
Installation
===============================================================================
1. Download the .NET framework 4.0 (if you haven't already)
http://www.microsoft.com/download/en/details.aspx?id=17851

2. Make sure the G19 Keyboard is plugged in.

3. Extract the PerfMon.zip to any location on disk and run "G19PerfMon.exe".


===============================================================================
FAQ / Troubleshooting
===============================================================================

1. To get the tray icon back just delete the "Settings.xml" file in the
PerfMon folder and restart the application.

2. The Configure button in the Logitech profiler might not work with this
application. You can however configure this application from the system tray
or directly from the "Settings.xml" located in the application folder.

3. The program currently only shows one physical CPU. It is compatible with
hyperthreading technology.

4. The button presses are checked every 250ms. For the pause button this might
mean that you have to press it a little longer than just a quick press (because
you might press it within 2 intervals of 250ms).

===============================================================================
Credits
===============================================================================

See the credits section in the Config Screen.

===============================================================================
Changelog
===============================================================================

Version 1.0.1a
	- Fixed a crash that occured because of a wrong working directory when
	  auto-starting.
	- Put a try-catch around the registry code in case it's run as a portable
	  on a restricted uesr account.

Version 1.0.1
	- Added the current active window information.
	- Added the option to take a (delayed) screenshot.
	- The Left and Right LCD arrow keys now control a slider that shows the
	  history information.
	- LCD key input is checked every 250ms.
	- It can now autostart with Windows using the registry (default).
	- The OK LCD button can be used to (un)pause the statistics gathering.

Version 1.0.0
	- First release