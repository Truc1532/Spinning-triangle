---DEPENDENCIES---
  OpenGL (renderer alteast 4.6)
  GL dev library (atleast 1.2)
  GLEW dev library (atleast 2.2)
  SDL2 dev library (atleast 2.0)
  GNU Compiler Collection
  make

---BUILD---
First make sure you're inside the programs directory:
  cd path/to/program/
(replace the dir names with the actual names of the directories)

Then let autogen.sh to run as a program
  chmod +x autogen.sh

Next run the autogen.sh:
  ./autogen.sh

If the configuration ended successfully you can run the makefile:
   make

Lastly enter:
  sudo make install

Now you can enter 'Spinning_triangle' in the terminal (no matter which directory) to run the program !
