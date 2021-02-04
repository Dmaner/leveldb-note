# Leveldb 源码阅读记录

> 对Leveldb源码进行分析学习

## 安装

```c++
git clone --recurse-submodules https://github.com/google/leveldb.git
mkdir -p build && cd build
cmake -DCMAKE_BUILD_TYPE=Release .. && cmake --build .
cd ..
sudo cp build/libleveldb.a /usr/local/lib/
sudo cp -r include/leveldb/ /usr/local/include/
```

## 参考

- [Leveldb](https://github.com/google/leveldb)