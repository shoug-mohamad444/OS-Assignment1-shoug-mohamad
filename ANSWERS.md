# Assignment Questions

## Instructions
Answer all 4 questions with detailed explanations. Each answer should be **3-5 sentences minimum** and demonstrate your understanding of the concepts.

---

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes?

**Your Answer:**

A process is an independent program with its own memory space, while a thread is a smaller unit of execution that runs داخل نفس العملية ويشاركها نفس الذاكرة. Threads are faster to create and require fewer resources compared to processes. In addition, communication between threads is easier because they share the same memory, while processes require mechanisms such as IPC. In this assignment, threads were used to simulate multiple processes efficiently without the overhead of creating separate processes. Each Process object is executed using a Thread in SchedulerSimulation.java.

---

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from your program output.

**Your Answer:**

In Round-Robin scheduling, if a process does not finish within its time quantum, it is paused and placed back into the ready queue. For example, the output shows a process running for a limited time and then being re-enqueued if it still has remaining time. This ensures that all processes get a fair chance to use the CPU. The re-queueing behavior prevents one process from dominating the CPU and improves fairness. It allows the scheduler to cycle through all processes efficiently.

---

## Question 3: Thread States

**Question**: A thread can be in different states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (P1) from your simulation.

**Your Answer:**

[A thread starts in the New state when it is created. When Thread.start() is called, it moves to the Runnable state and then to Running when the CPU executes it. During execution, the thread may enter a Waiting or sleeping state when Thread.sleep() is used. After completing its task, the thread enters the Terminated state. In this assignment, each process thread follows this lifecycle when scheduled using the Round-Robin algorithm. A process may run, pause, and then either re-enter the queue or finish execution.
---

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. Explain why this scheduling algorithm works well for those scenarios.

**Your Answer:**

Multithreading is widely used in real-world applications such as web servers, where multiple user requests are handled simultaneously using threads. Another example is media players, where separate threads handle video playback, audio, and user controls at the same time. Round-Robin scheduling can be applied to ensure fair resource usage among tasks. These concepts are similar to this assignment, where multiple processes share CPU time. Multithreading improves performance, responsiveness, and system efficiency.

---

## Summary

**Key concepts I understood through these questions:**
1. The difference between threads and processes, especially in terms of memory sharing and performance.
 2. How Round-Robin scheduling works and how processes are re-enqueued to ensure fairness.
 3. The thread lifecycle in Java and how threads move between different states during execution.
**Concepts I need to study more:**
 1. Advanced multithreading concepts such as synchronization and avoiding race conditions.
 2. Handling complex concurrency issues like deadlocks and thread safety in larger systems. 
