# C++ Multithreading Examples

A small collection of C++ examples for practicing core multithreading and concurrency concepts.

## Topics

1. **Thread creation**  
   Starting and running work using `std::thread`.

2. **Returning values from threads**  
   Passing results back from work executed in another thread.

3. **Data races**  
   Demonstrating what happens when multiple threads modify shared data without proper synchronization.

4. **Mutexes and locking**  
   Protecting shared resources using mutexes and locking mechanisms.

5. **Thread-safe counters**  
   Safely updating shared counters from multiple threads.

6. **Timeouts**  
   Waiting for thread-related operations with a time limit.

7. **Thread synchronization**  
   Coordinating threads using `std::this_thread::yield()` and `std::condition_variable`.

8. **Deadlocks**  
   Showing how deadlocks can occur when multiple mutexes are acquired in conflicting orders.

## Build

The examples are built with CMake:

```bash
cmake -S . -B build
cmake --build build