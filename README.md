# kicad-lib
My component and footprint library for the [KiCad PCB design suite](http://www.kicad-pcb.org/)

## Quick start
  1. Clone to wherever (I like `~/projects`) and `$ cd /path/to/kicad-lib`
  2. Edit `kicad.sh` so that `KISYSMOD` is defined as `/path/to/kicad-lib/footprints`
  3. `$ chmod +x linklibs` (if not in linux, directories in this script should be edited accordingly)
  4. `$ ./linklibs` (this will ask for your sudo password)
  5. logout and log back in - kicad will now use these footprint files
  6. for each new kicad project, select the component libraries manually using Preferences > Library in eeschema
