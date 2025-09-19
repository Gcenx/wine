## Game Porting Toolkit (wine)

This branch contains Apples modified version of wine used for [game-porting-toolkit](https://developer.apple.com/games/game-porting-toolkit/) based on [crossover-sources-22.1.1](https://media.codeweavers.com/pub/crossover/source/crossover-sources-22.1.1.tar.gz). With some additinal cherry picked commits from upstream wine so it defaults to Win10 19043.

### Requirements
- Apple Silicon mac running macOS Sequoia or greater
- 16GB RAM or greater

### Build requirments
- cctools-port (cctools-973.0.1-ld64-609)
- llvm-cx (codeweavers custom llvm toolchain for wine32on64)
- MacOSX13.sdk
- mingw-w64 v12
