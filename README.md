\# C++ Multithreading Examples



This repository contains small C++ examples demonstrating common multithreading and concurrency concepts.



\## Concepts Covered



1\. \*\*Creating Threads\*\*  

&#x20;  Basic usage of `std::thread` and running functions concurrently.



2\. \*\*Returning Values from Threads\*\*  

&#x20;  Demonstrates how results can be obtained from work performed in another thread.



3\. \*\*Data Races\*\*  

&#x20;  Shows what can happen when multiple threads access and modify shared data without synchronization.



4\. \*\*Mutexes and Locking\*\*  

&#x20;  Demonstrates locking mechanisms such as `std::mutex` and lock guards for protecting shared resources.



5\. \*\*Thread-Safe Counters\*\*  

&#x20;  Shows how shared counters can be updated safely when accessed by multiple threads.



6\. \*\*Timeouts\*\*  

&#x20;  Demonstrates how to wait for an operation for a limited amount of time.



7\. \*\*Thread Synchronization\*\*  

&#x20;  Examples of synchronizing multiple threads using:

&#x20;  - `std::this\_thread::yield()`

&#x20;  - `std::condition\_variable`



8\. \*\*Deadlocks\*\*  

&#x20;  Demonstrates how deadlocks can occur when multiple mutexes are locked in an unsafe order.



\## Build



The project uses CMake.



```bash

cmake -S . -B build

cmake --build build

