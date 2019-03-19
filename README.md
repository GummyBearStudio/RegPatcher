RegPatcher for Windows 10
This is a set of useful registry entries that either disable or enable certain features of Windows 10. The batch file is used to shutdown PC ensuring that registry entries are correct (requires admin privileges to run regedit command) - designed to shutdown PCs with dual boot installations as hiberboot tends to enable itself after upgrading OS which can cause damage to hard drives - shutting down with this prevents such situations.

Summary:
askupdate - makes Windows ask before downloading and installing an upgrade (may not work since some version)
disableosupgrade - stop Windows from upgrading
driversearch - disable automatic driver search
driverupdate - exclude drivers from Windows Update
noautoreboot - disable auto reboot with logged on users
noautoupdate - disable auto update in Windows Update
nohiberboot - disables hiberboot option in Power Management which is recommended (or even necessary) on DUAL BOOT MACHINES
noschedulereboot - disable auto reboot at scheduled time
showcpulimit - brings CPU frequency limit setting back to Power Managment