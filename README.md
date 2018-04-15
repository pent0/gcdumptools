# gcdumptools

Gamecube dump tools ported to C++ 17, cross platform
Include three tools, as I used for dumping Animal Crossing on Linux:
- yaz0dec: A Yaz0 decoder
- rarcdump: Extract RARC file
- gcmdump: Dump GCM file

All theses file used dirent, I simply ported them to C++17 with filesystem.
