cmake_minimum_required(VERSION 3.8)
project(FileSystem)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp
        Buf.h
        CMakeLists.txt
        DirectoryEntry.h
        InitFS.cpp
        INode.h
        MyFileSystem.cpp
        MyFileSystem.h
        SuperBlock.h)
add_executable(FileSystem ${SOURCE_FILES})