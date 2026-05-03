<img src="OnoPKG.png" width="1000">

# What is OnoPKG?

OnoPKG is a small package manager for OnOS <br>
Mostly vibe coded since ion know much C but at least it works <br>

# How to compile it

1. git clone https://github.com/TheRealOnogen/OnoPKG.git
2. cd OnoPKG
3. gcc -O2 -o onopkg onopkg.c -lcurl -lz -larchive -lm -lpthread

# Usage

  `onopkg <package>`      Download package + dependencies <br>
  `onopkg -S <package>`    Search, download and install to /  (requires root) <br>
  `onopkg --sync`          Scan system and populate installed DB <br>
  `onopkg -R <package>`    Remove package from system         (requires root) <br>
  `onopkg -Rd <package`   Remove package + orphaned deps     (requires root) <br>
  `onopkg --list`          List all packages in installed DB <br>
