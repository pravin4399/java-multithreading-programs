# Java-Multithreading and Concurrency
---
### Let's explore and learn about multi-threading and concurrency.

## [Multithreading Interview Questions](https://www.digitalocean.com/community/tutorials/java-multithreading-concurrency-interview-questions-answers)
-[x] What is the difference between Process and Thread?
- > ```Program``` - A program is set of instructions(a rule or a statement). Program is passive.
- > ```Process``` - A program under execution is called a Process. Process is active. Processes do not share memory.
- > ```Thread``` - A unit or portion of Process that executes independently and A Process can have many threads running parallely.
  > Multiple Threads share common heap memory of the parent Process. Each Thread has It's own Thread Stack.

- [ ] What are the benefits of multithreaded programming?
- > 1. To create high performing applications.
- > 2. Independent tasks can be executed by multiple threads such applications can use multi threading and hence improve performance.
-[ ] What is difference between user Thread and daemon Thread?
-[ ] How can we create a Thread in Java?
-[ ] What are different states in lifecycle of Thread?
-[ ] Can we call run() method of a Thread class?
-[ ] How can we pause the execution of a Thread for specific time?
-[ ] What do you understand about Thread Priority?
-[ ] What is Thread Scheduler and Time Slicing?
-[ ] What is context-switching in multi-threading?
-[ ] How can we make sure main() is the last thread to finish in Java Program?
-[ ] How does thread communicate with each other?
-[ ] Why thread communication methods wait(), notify() and notifyAll() are in Object class?
-[ ] Why wait(), notify() and notifyAll() methods have to be called from synchronized method or block?
-[ ] Why Thread sleep() and yield() methods are static?
-[ ] How can we achieve thread safety in Java?
-[ ] What is volatile keyword in Java
-[ ] Which is more preferred - Synchronized method or Synchronized block?
-[ ] How to create daemon thread in Java?
-[ ] What is ThreadLocal?
-[ ] What is Thread Group? Why it’s advised not to use it?
-[ ] What is Java Thread Dump, How can we get Java Thread dump of a Program?
-[ ] What is Deadlock? How to analyze and avoid deadlock situation?
-[ ] What is Java Timer Class? How to schedule a task to run after specific interval?
-[ ] What is Thread Pool? How can we create Thread Pool in Java?
-[ ] What will happen if we don’t override Thread class run() method?
## [Java Concurrency Interview Questions](https://www.digitalocean.com/community/tutorials/java-multithreading-concurrency-interview-questions-answers)
-[ ] What is atomic operation? What are atomic classes in Java Concurrency API?
-[ ] What is Lock interface in Java Concurrency API? What are it’s benefits over synchronization?
-[ ] What is Executors Framework?
-[ ] What is BlockingQueue? How can we implement Producer-Consumer problem using Blocking Queue?
-[ ] What is Callable and Future?
-[ ] What is FutureTask class?
-[ ] What are Concurrent Collection Classes?
-[ ] What is Executors Class?
-[ ] What are some of the improvements in Concurrency API in Java 8?