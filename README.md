# HPRC KiCad Component Library

Library to use in NCSU HRPC projects like FIRM and Airbrakes

# Setup

1. Clone this repo and copy the path
2. Open KiCad
3. Click **Preferences --> Configure Paths** 
4. Click **"+"** button, set "Name" to **KICAD_HPRC_LIB** and paste the path into "Path", click "Ok"
5. Click **Preferences --> Manage Symbol Libraries**
6. Click **"+"**, set "Nickname" to "HPRC", set "Library Path" to **${KICAD_HPRC_LIB}/sym-lib-table**, click "Ok"
5. Click **Preferences --> Manage Footprint Libraries**
6. Click **"+"**, set "Nickname" to "HPRC", set "Library Path" to **${KICAD_HPRC_LIB}/fp-lib-table**, click "Ok"

# Adding Library Folders and Components

The KiCad right-click context menu should be sufficient to manage libraries. Make sure library folders are prefixed by **"HPRC_"** 

### Symbols

Use the symbol editor and right-click on library folders to add new components

### Footprints

Use the footprint editor and right-click on library folders to add new components. If adding a 3D model, make sure to check the **"Embed"** option.