# Assignment Questions

## Instructions
Answer all 4 questions with detailed explanations. Each answer should be **3-5 sentences minimum** and demonstrate your understanding of the concepts.

---

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes?

**Your Answer: A thread is a smaller unit of execution that operates inside a process and shares memory, whereas a process is an independent program with its own memory and system resources. Because each process needs its own memory and system resources, processes are heavier and more costly to produce, while threads are lighter and easier to manage.

To effectively replicate CPU scheduling in this assignment, threads were employed in place of processes. The ready queue and process execution are made simpler because all threads share the same memory. Because of this, threads are better suited for using scheduling methods such as Round-Robin.**


---

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from your program output.

**Your Answer: A process in Round-Robin scheduling gets pushed to the end of the ready queue if it does not complete within the allotted time quantum. This prevents any process from controlling the CPU and guarantees that every process has an equal opportunity to run.**


Example from my output:
```
▶ P2 executing quantum [4000ms]
⏸ P2 completed quantum 4000ms │ Overall progress: 44%
Remaining time: 5010ms
↻ P2 yields CPU for context switch
➕ P2 (Priority: 4) added to ready queue

```
**Explanation of example:**

In this instance, process P2 failed to complete its execution within the allotted 4000 ms. With 5010 milliseconds left, it gave up the CPU. After that, the scheduler put P2 at the end of the ready queue so that other processes might run before it had another chance.
---

## Question 3: Thread States

**Question**: A thread can be in different states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (P1) from your simulation.

**Your Answer:**

1. **New**: P1 is in the New state when the thread is created using `new Thread(process)` but has not started execution yet.

2. **Runnable**: P1 becomes Runnable when it is added to the ready queue, as shown in the output:
➕ P1 (Priority: 2) added to ready queue

3. **Running**: P1 enters the Running state when `currentThread.start()` is called and begins executing:
▶ P1 executing quantum [2286ms]

4. **Waiting**: P1 enters the Waiting state (simulated using `Thread.sleep()`) during execution, where the thread pauses to simulate CPU processing time.

5. **Terminated**: P1 reaches the Terminated state after completing execution:
✓ P1 finished execution!


---

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. Explain why this scheduling algorithm works well for those scenarios.

**Your Answer:**

### Example 1: [Web Server]

**Description**: 
A web server manages several client requests at once, each of which is handled by a different thread.

**Why Round-Robin works well here**: 
Every request receives an equal amount of CPU time thanks to Round-Robin. This enhances responsiveness for all users and keeps the server from being blocked by a single request.



### Example 2: [Operating System Task Scheduling]

**Description**: 
Operating systems oversee several concurrently running apps, each of which demands CPU time.

**Why Round-Robin works well here**: 
By assigning a set time quantum to each process, round-robin scheduling guarantees equity. This keeps processes from starving and enhances system responsiveness.
---

## Summary

**Key concepts I understood through these questions:**
1. The distinction between threads and processes
2. Round-Robin scheduling behavior
3. The lifespan and execution stages of threads

**Concepts I need to study more:**
1. Synchronization of threads
2. Race situations and deadlocks
