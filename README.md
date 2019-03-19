RegPatcher for Windows 10<br>
This is a set of useful registry entries that either disable or enable certain features of Windows 10. The batch file is used to shutdown PC ensuring that registry entries are correct (requires admin privileges to run regedit command) - designed to shutdown PCs with dual boot installations as hiberboot tends to enable itself after upgrading OS which can cause damage to hard drives - shutting down with this prevents such situations.
<br><br>
Summary:<br>
askupdate - makes Windows ask before downloading and installing an upgrade (may not work since some version)<br>
disableosupgrade - stop Windows from upgrading<br>
driversearch - disable automatic driver search<br>
driverupdate - exclude drivers from Windows Update<br>
noautoreboot - disable auto reboot with logged on users<br>
noautoupdate - disable auto update in Windows Update<br>
nohiberboot - disables hiberboot option in Power Management which is recommended (or even necessary) on DUAL BOOT MACHINES<br>
noschedulereboot - disable auto reboot at scheduled time<br>
showcpulimit - brings CPU frequency limit setting back to Power Managment<br>