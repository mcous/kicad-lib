# kicad-lib
My component and footprint library for the [KiCad PCB design suite](http://www.kicad-pcb.org/)

## Quick start
  1. Clone to wherever
  2. Close KiCad
  3. Put the new libraries in a project:
    * `$ ./setlibs path/to/project.pro` to completely replace the libraries in a project
    * `$ ./setlibs --append path/to/project.pro` to append the libraries to a project (new libraries will have lower precedence than existing libraries)
    * `$ ./setlibs --prepend path/to/project.pro` to prepend the libraries (new libraries will have higher precedence)
    * `$ ./setlibs --help` to see your other options
  4. Re-open KiCad and enjoy the new libraries
