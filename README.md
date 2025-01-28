# File

A program that implements a Unix-like file system in C.

### Description

The file system is made up of 3 layers. From top to bottom, these are:

- fs – user-level filesystem, with functions like fsOpen, fsRead, fsSeek, fsClose.
- bfs – functions internal to BFS such as bfsFindFreeBlock, bfsInitFreeList.
- bio - lowest level block IO functions: bioRead and bioWrite.

Each layer is represented by a .c file.

---

Credits:<br>
Starter code provided by Yusuf Pisan<br>
Implementation by Dhimitri Mano
