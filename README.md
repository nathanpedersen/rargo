# rargo

C build environment creater inspired by cargo.

How to use:

1. Have GTest installed on your machine.
```
sudo apt-get install libgtest-dev
sudo apt-get install cmake # install cmake
cd /usr/src/gtest
sudo cmake CMakeLists.txt
sudo make
sudo cp lib/*.a /usr/lib
```
2. Put rargo in your /usr/bin/ directory.
3. make a project directory.
4. in your project directory, run rargo init.

Your project directory should look like this. 

```
.
├── build
├── CMakeLists.txt
├── .git
├── include
├── tests
│   └── test.cpp
└── src
    └── main.c
```

Test with rargo build then rargo run.

You can edit this quite easily to do what you want.

# options

```
i | init 	Initialize a project in current directory.
b | build 	Used in project root directory. Builds project. Binary will be in build directory.
r | run 	Runs current build of project
t | test    Runs GTest tests
h | help 	Prints this help prompt
```
