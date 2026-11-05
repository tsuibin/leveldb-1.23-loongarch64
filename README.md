# LevelDB 1.23 on loongarch64

    CXXFLAGS=-fPIC cmake -B build -DCMAKE_INSTALL_PREFIX=$PREFIX \
          -DLEVELDB_BUILD_BENCHMARKS=OFF -DLEVELDB_BUILD_TESTS=OFF .
    cmake --build build -j4 && cmake --install build

零补丁。

## 更新（2026-11-04）

已随 Doris BE 全量编译与链接验证通过（0 错误）。零补丁、零 loongarch 改动。
