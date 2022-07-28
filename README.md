# Project 1: Build My World


## Build
1. Verify that you have the following installed.
    * ROS
    * Cmake
    * gcc/g++
    * Git

2. Clone the repo to the folder of your choice.

    ```
    $ git clone https://github.com/yabdulra/Build-My-World.git 
    ```

3. Create a build directory and compile the code:

    ```
    $ cd <path to folder>/Project1
    $ mkdir build && cd build
    $ cmake ../
    $ make
    $ export GAZEBO_PLUGIN_PATH=${GAZEBO_PLUGIN_PATH}:<path to folder>/Project1/build
    ```
    Note: you need to change `<path to folder>` with the specific path on you computer.

## Launch
Launch the world file
    
```
$ cd <path to folder>/Project1/world
$ gazebo YusahOffice.world
```

![world](https://user-images.githubusercontent.com/61895971/181424749-b25a78cd-692f-43d1-885c-5bb4dc031ae6.png)

