# rargo

C++ build environment creater inspired by cargo.

How to use:

1. Put rargo in your /usr/bin/ directory.
2. make a project directory.
3. in your project directory, run rargo init.
4. run rargo build.
5. run rargo run.

Your project directory should look like this. 

```
.
├── build
├── .ccls
├── CMakeLists.txt
├── .git
├── include
└── src
    └── main.cpp
```

# options

```
i | init 	Initialize a project in current directory.
b | build 	Used in project root directory. Builds project. Binary will be in build directory.
r | run 	Runs current build of project
h | help 	Prints this help prompt
```
