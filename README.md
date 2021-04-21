# docker-cpp-env-ubuntu-x64

C++ x86_64 開發環境，保含下面軟體：

- CMake
- Conan
- SSH server
- GDB server

## 使用方法

### Conan based projects

```
docker run --rm -it -v $(pwd):/project vswteam/cpp-env-ubuntu-x64:latest "mkdir -p build && cd build && conan install .. && conan build .."
```
