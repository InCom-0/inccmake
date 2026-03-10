[inccmake](https://github.com/InCom-0/inccmake) is a repository containing collection of CMake scripts, toolchains, modules and various other code related to using CMake in projects effectively. This repository mostly aggregates content of other repositories in 1 place and is putting it in a sensible structure and removes the extra things from those repositories that are not really required. The aim is to be able to include all these things from one place.<br><br>
One may use submodule or a subtree to include this in other projects. However, it might be best to simply copy&paste (otherwise known as 'vendoring') just the content that one wants/needs directly into your project's repo, since the content of this repo is unlikely to change often and one does not really need to track the changes separately from the upstream projects.
<br><br>
<i>Note: The 'main' branch contains just this readme. The content meant for inclusion in other projects in located in the 'aggregate' branch.</i>
<br><br>

What it includes:
1) CMake scripts cleaved from 'cpp-best-practices' CMake template project by Jason Turner https://github.com/cpp-best-practices/cmake_template ('lefticus' folder)
    * Note that 'lefticus' also includes CMake package manager [CPM.cmake](https://github.com/cpm-cmake/CPM.cmake)
2) CMake toolchains for compiling C++ on Windows by Mark Shofield https://github.com/MarkSchofield/WindowsToolchain ('WindowsToolchain' folder)
3) Collection of additional CMake modules to be able to 'find_package()' more different libraries by the KDE project https://github.com/KDE/extra-cmake-modules ('KDE_extramodules' folder)
4) Several utility scripts written by the author ('incom' folder)

<br><br>