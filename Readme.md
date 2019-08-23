# Makefile Templates

There are two Makefile templates  in this repository and they are good for small projects with minimal or no dependencies. The templates offer the following commands:

`make`

`make all`

`make clean`

## Makefile-SharedLib

This Makefile template can be use to build a shared library. Just make the following changes:

* replace `TARGETNAME` by the name of the shared library.
* replace `include_path` with the required include directory. Add more `-I` macros as required.
* replace `lib_path` with the required library directory. Add more `-L` and  `-Wl,-rpath,` macros as required.
* Added libraries on which the target depends on in `LIBRARIES`.
* Updated `SOURCES`.

## Makefile-Executable

This Makefile template can be use to build am executable. Just make the following changes:

* replace `TARGET_NAME` by the name of the executable.
* replace `include_dir` with the required include directory. Add more `-I` macros as required.
* replace `lib_path` with the required library directory. Add more `-L` and  `-Wl,-rpath,` macros as required.
* Added libraries on which the target depends on in `LIBRARIES`.
* Updated `SOURCES`.