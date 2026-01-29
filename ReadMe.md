Installation Environment (01.29.2026)

-  FileToy is designed to run in a Windows 11 or Windows 10 version 1607 (Build 14393) or later environment.
-  It is packaged and runs as a 64-bit application only.
-  It uses less than 3 MB of disk space and does not "hook" into the OS per-se
-  It installs files and settings into:
     - Application disk files:    C:\Users\<username>\AppData\Local\FileToy
     - Registry settings:         HKEY_CURRENT_USER\Software\FileToy
     - Registry uninstall:        HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Uninstall
-  Temporary files and folders created during running the application are deleted:
     - on normal closing of the application
     - on application startup after an application crash
     - on uninstalling the application


Removal:

-  “Uninstall" deletes all the files and registry settings that were installed by the application.
-  “Uninstall” deletes all temporary folders and files created by the application.
-  Only items (remnants) created by the Microsoft Windows OS itself remain on the system.
