# fast drawing in C

Draw a rectangle and handle mouse clicks in C with only SDL2. It compiles down to 29664 bytes on my end, with default optims.

Building the main file should be trivial with any install of SDL2 (well-documented for virtually all platforms, even building from source seems trivial). The code was created, compiled and tested with VS Code on Ubuntu. The only relevant file is main.c whereas the other files are the VS Code project so I left them out.

The SDL lib actually feels fanstatic to use and seems to me like an excellent example of a solid API exclusively in C (no C++)