# ARVK

[Vulkan](https://en.wikipedia.org/wiki/Vulkan) wrappers for C++.

## It makes use of:
* [RAII](https://en.wikipedia.org/wiki/Resource_acquisition_is_initialization)
* [Builder Patterns](https://en.wikipedia.org/wiki/Builder_pattern)

## Usage

1. Clone the repository
2. Go into the folder with `CMakeLists.txt`
3. Run:
```console
$ mkdir build && cd build
$ cmake .. & cmake --build .
```

> [!TIP]
> Check [Building with CMake](docs/building.md) for an advanced explanation

## Samples
#### Use builder patterns to create advanced Vulkan structures easily
```c++
#include <arvk.hpp>

int main()
{
    arvk::PipelineBuilder pipelineBuilder;
}
```

## Platforms
* Windows (msvc)
* Linux **(WIP)**

## Contact
#### <a href="https://mail.google.com/mail/?view=cm&fs=1&to=karol.filanski@gmail.com"> Email me </a>

---

<p align="center">
    Copyright &copy; 2026 <a href="https://github.com/21Charles" target="_blank">Karol Filański</a>
</p>

<p align="center">
    <a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-GPLv3-brightgreen?style=for-the-badge"/></a>
</p>