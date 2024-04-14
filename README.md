glad
====

Glad for use in DMU C++ modules.

Include you CMakeLists.txt using FetchContent.

## Example

```c
FetchContent_Declare(
  glad
  GIT_REPOSITORY https://github.com/SimonCouplandDMU/DMUGlad.git
  GIT_TAG        gl4.6_core_no_ext
 )
 
 FetchContent_MakeAvailable(glad)
```


