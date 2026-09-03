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

# Adding Library Folders

1. Add the footprint folder or symbol in "footprints" or "symbols"
2. Open the corresponding "fp-" or "sym-" file
3. Copy and paste the last entry in the file and change the name and path accordingly
