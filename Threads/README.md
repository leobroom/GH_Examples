## ContinuousLoop

C# Example

### File

[Threads_ContinuousLoop.gh](../../tree/main/Threads/Threads_ContinuousLoop.gh "Continuous Loop within a Thread in Grasshopper")

### Explanation
The Grasshopper script shows an example how to deal with threads in the C# Script Editor.

### Summary
A thread gets initialiazed and started. The Thread executing a method, which fills during a never ending while loop a static Point3d list with random entities. After 40 added Points, the get removed one by one. When the component is stopped (start == false), the current thread is aborted and through an event delegate - the component will recalculate.


> What is a thread?

[https://www.tutorialspoint.com/csharp/csharp_multithreading.htm](https://www.tutorialspoint.com/csharp/csharp_multithreading.htm)


> Why Multithreading?

[https://www.geeksforgeeks.org/c-sharp-multithreading/](https://www.geeksforgeeks.org/c-sharp-multithreading/)


> Why Thread safety is important

[https://www.c-sharpcorner.com/UploadFile/1c8574/thread-safety369/](https://www.c-sharpcorner.com/UploadFile/1c8574/thread-safety369/)


> Threaded vs. Non-Threaded applications

Why you have to invoke the ExpireSolution Method, rather then calling it inside the thread:

[https://www.grasshopper3d.com/forum/topics/triggering-solution-refresh?overrideMobileRedirect=1&id=2985220%3ATopic%3A170034&page=1](https://www.grasshopper3d.com/forum/topics/triggering-solution-refresh?overrideMobileRedirect=1&id=2985220%3ATopic%3A170034&page=1)

Credit to: David Rutten, Eric Anastas
