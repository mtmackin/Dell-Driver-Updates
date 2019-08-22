# Dell-Driver-Updates-PSADTK
Dell Driver update w/ Powershell Application Deployment ToolKit. This package for SCCM will use Dell's Command Update command line to scan the computers for hardware, then cross check it with Dell's model catalog and install the drivers from Dell's site. This includes Bios and Drivers. 

Note: Make sure if you have a BIOS password on the system you update the PW in the script, if you do not employ a bios pw commment out the cctk lines of the code.
