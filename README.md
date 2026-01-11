# Getting Started



1. Build both submodules
    - Stockfish: `make -j help` in the `src` directory
    - chess-library: `meson setup build` and `meson compile -C build`

2. Create a directory `bin/` in the root directory, and then copy the `stockfish` executable from `include/Stockfish/`
3. Access the stockfish binary by running the executable in `bin/`, and the `chess-library` API from the `chess::` namespace with `#include<chess.hpp>` 
4. Build the project executable with `meson`.


