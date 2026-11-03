# LevelDB 1.23 on loongarch64

    CXXFLAGS=-fPIC cmake -B build -DCMAKE_INSTALL_PREFIX=$PREFIX \
          -DLEVELDB_BUILD_BENCHMARKS=OFF -DLEVELDB_BUILD_TESTS=OFF .
    cmake --build build -j4 && cmake --install build

零补丁。
