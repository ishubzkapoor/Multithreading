# CMakeList.txt : CMake project for Multithreading, include source and define
# project specific logic here.
#
# CMakeLists.txt

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(thread1 "1.thread.cpp")
add_executable(return_from_function "2.return_from_function.cpp")
add_executable(data_race "3.Data_race.cpp")
add_executable(locking "4.locking.cpp")
add_executable(thread_safe_counters "5.thread_safe_counters.cpp")
add_executable(timeout "6.timeout.cpp")
add_executable(sync_yield "7.1sync_devices_yield.cpp")
add_executable(sync_condition_variable "7.2sync_devices_condition_variable.cpp")
add_executable(deadlock "8.deadlock.cpp")