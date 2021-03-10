# Yardland

Yardland is a C++ library for dealing with old computer system emulation, Originally made to emulate systems based on CPUs from the 65xx Architecture.

## Installation

Use the package manager [CPM](https://github.com/cpm-cmake/CPM.cmake) to install Yardland.

```CMake
cmake_minimum_required(VERSION 3.14)

# create project
project(MyProject)

# add executable
add_executable(tests tests.cpp)

# add dependencies
include(cmake/CPM.cmake)
CPMAddPackage("gh:eliotvonecklie/libyardland@1.0.0")

# link dependencies
target_link_libraries(tests libyardland)
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)