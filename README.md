# Operability between Objective-C and C++ using CMake

Something, when targeting macOS, you want to call an Objective-C method (e.g., from Cocoa) from your C++ code.

This little test project try to do that.

## Dependencies

- macOS 11+ (Maybe earlier is ok, but I haven't tested)
- Xcode 12.3+ (Maybe earlier is ok, but I haven't tested)
- CMake 3.16+ (Objective-C support added in Cmake 3.16)

## How to build

```
git clone https://github.com/dalboris/test-objective-c-cpp-cmake
cd test-objective-c-cpp-cmake
mkdir build
cd build
cmake ..
cmake --build .
```
