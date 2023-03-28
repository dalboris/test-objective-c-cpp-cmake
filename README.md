# Operability between Objective-C and C++ using CMake

Sometimes, when targeting macOS, you want to call an Objective-C method (e.g., from Cocoa) from your C++ code.

Here is a minimal test project that does just that.

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

## How to run

```
./HelloWorld
```

Output:

```
2023-03-28 19:37:46.970 HelloWorld[10606:200462] Hello, World!
```
