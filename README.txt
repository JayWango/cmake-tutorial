This directory contains source code examples for the CMake Tutorial.
Each step has its own subdirectory containing code that may be used as a
starting point. The tutorial examples are progressive so that each step
provides the complete solution for the previous step.

Following tutorial from this link below:
https://cmake.org/cmake/help/latest/guide/tutorial/index.html

**Notes to Self**

In big projects, its good to separate source and build directories. 
Source directories contain all of the source code, such as .cpp and .h files, that are needed to generate the build system.
Build directories keeps the compiled files and temporary build artifacts separate from the source directory, making it easier to clean, rebuild, and support multiple build configurations 