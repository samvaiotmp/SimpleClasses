cmake_minimum_required(VERSION 3.7)
project(SimpleClasses)

set(CMAKE_CXX_STANDARD 11)

include_directories(Header)


set(SOURCE_FILES  src/SimpleClasses.cpp src/Account.cpp src/Transaction.cpp Header/Transaction.h Header/Account.h)
add_executable(SimpleClasses ${SOURCE_FILES})