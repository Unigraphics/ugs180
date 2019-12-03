# ugs180
 Unigraphics v.18.0 (release version)
 
Running Unigraphics.

1.Step - create disk.cmd
 Create virtual disk U:\

2.Step - edit ug180 - hostname.txt
 Modify file ug180.dat. Replacing <host> with the <computer name>
 
SERVER host ANY 740
VENDOR uglmd U:\UGFLEXLM\uglmd.exe

3.Step - UniGraphicsLicense.bat
  console window don't close.

4.Step - UniGraphicsRun.bat
  setting env and running UG

---
After working, can start Step-stop.cmd
This file kill uglmd.exe procces and delete disk U:\

-------------------------------------------------------------------------------

