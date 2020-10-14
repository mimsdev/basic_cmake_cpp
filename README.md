# basic_cmake_cpp
Basic CMake sample for C++ project (using GitHub GoogleTest CI)

Dev test/done with CMake v3.16 (install via snap) on Ubuntu 20.04 with:
 - Shell/Standard text editor (GEdit/SublimeText/...)
 - Visual Studio Code (VSCode install via snap) 
 - JetBrain CLion 2020.2 (evaluation version - paid software)

## Roadmap
 - CMake basic example in C++ (basic class hierachy)
 - Try to manage/test different C++ standard 98, 11, 14, 17, 20
 - Add source code static analysis (cppcheck, visual check in VSCode using ESLint extension)
 - Add GTest (GoogleTest framework)
 - Add CI / GitHub Actions (Workflow)
 
### Basic CMake stucture
Project repository will contain

```
 Project repository
  |-- build
  |-- cmake
{ |--- include }
  |-- src
  |-- main
  |-- test
  |-- third_party
  CHANGELOG.md
  CMakeLists.txt
  LICENCE.md
  README.md
  .gitignore
  ...
  
```
Folders
  - **build** for cmake build generation
  - **cmake** for macro/functions/cross-compilation-plateform settings .cmake files
  - **include** optionaly to share public headers
  - **src** for c++ source and header for libraries/project functionalities
  - **main** for main application (can be basic demo like hello world or basic test)
  - **test** for testing purpose (using framework like GTest, CTest, cpp-unit, ...)
  - **third-party** for external sources (libraries, framework, ...). Can be redirection to other github repo
Files
  - Changelog.md for list of change (improovement/fix) and version number with date of this project
  - CMakeLists.txt for general CMake file for this project uncluding special cmake files and specific CMakeLists.txt contained in every folder
  - LICENCE.md for the licence used for this project
  - README.md for information/description of the project (this file)

  
