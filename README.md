# rargo

C++ build environment creater inspired by cargo.

How to use:

1. Put rargo in your /usr/bin/ directory.
2. make a project directory.
3. in your project directory, run rargo init.

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

Test with rargo build then rargo run.

You can edit this quite easily to do what you want.
The .ccls file is for a language server for coc.nvim.

# options

```
i | init 	Initialize a project in current directory.
b | build 	Used in project root directory. Builds project. Binary will be in build directory.
r | run 	Runs current build of project
h | help 	Prints this help prompt
```
