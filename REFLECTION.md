# Reflection Questions

## Instructions
Answer the following questions about your learning experience. Each answer should be **at least 5-7 sentences** and show your understanding.

---

## Question 1: What did you learn about multithreading?

**Your Answer: This assignment taught me how multithreading enables several processes to run simultaneously within a single program. I was aware of the creation and management of threads as well as the fact that each thread is a distinct execution unit. The way threads transition between several stages, including New, Runnable, Running, Waiting, and Terminated, is one crucial idea I picked up.

Using the Round-Robin method, I also gained a practical understanding of how scheduling operates. It made it easier for me to comprehend how the CPU allocates time among processes in an equitable manner. The way threads can mimic actual CPU behavior through time quantum and context flipping intrigued me.

I became aware of the value of multithreading in creating responsive and effective systems as a result of this assignment, particularly when several tasks must be completed simultaneously.**

[Write your answer here. Discuss specific concepts like thread creation, thread states, how threads execute concurrently, what surprised you, etc.]

---

## Question 2: What was the most challenging part of this assignment?

**Your Answer: Understanding how the scheduling loop operates and how processes are re-added to the ready queue was the most difficult aspect of this task. Tracking what occurs once a process completes its quantum and how context flipping is handled was initially perplexing.

Correctly implementing the additional features, particularly figuring out the waiting period and updating it just before execution, was another challenge. In order to maintain the correct logic, I had to be cautious about where to put specific lines of code.

Additionally, it was a little challenging to arrange the results in a clear and understandable manner, particularly when it came to correctly aligning the waiting time summary table.**

[Describe the specific challenge. Was it understanding the code? Implementing a feature? Using Git? Explain what made it difficult and how it relates to the course concepts.]

---

## Question 3: How did you overcome the challenges you faced?

**Your Answer: I divided the problem into manageable chunks and concentrated on comprehending each code segment step by step in order to get over these obstacles. I thoroughly examined the current code and tracked the scheduler's operation.

In order to confirm that every feature was operating as intended, I also tested the program several times and looked at the results. I checked variable values and made sure the reasoning was proper when something didn't function as I had anticipated.

I also looked over the course materials and used logic to determine where to include new features like waiting time updates and context switch counts. This strategy gave me more self-assurance and enabled me to finish the task successfully.**

[Describe your problem-solving approach. Did you read documentation? Ask for help? Debug systematically? What resources did you use? What strategies worked?]

---

## Question 4: How can you apply multithreading concepts in real-world applications?

**Your Answer: In practical applications, multithreading is frequently employed to enhance responsiveness and performance. Web browsers, for instance, use numerous threads to process user input, play videos, and load sites all at once without freezing.

Mobile apps are another example, where background processes like data downloads and notifications operate in different threads while the user interacts with the program seamlessly.

Furthermore, multithreading is crucial to operating systems' ability to effectively manage numerous programs. I was able to comprehend how these ideas are used in actual systems thanks to this project.**

[Give specific examples from real applications you use (web browsers, games, mobile apps, etc.). Explain why threads are useful in those scenarios. Connect to what you learned in this assignment.]

---

## Additional Reflections (Optional)

### What would you like to learn more about?
I would like to learn more about advanced multithreading concepts such as thread synchronization, race conditions, and deadlocks. These topics are important when multiple threads access shared resources at the same time. I want to understand how to prevent errors and ensure safe execution in concurrent systems. 
In addition, I am interested in learning about real-world implementations of these concepts in operating systems and large-scale applications. This will help me connect theoretical knowledge with practical usage.

[Any topics related to threading, concurrency, or operating systems that you're curious about?]

---

### How confident do you feel about multithreading concepts now?
I consider myself to be intermediate. The fundamental ideas of multithreading, such as thread creation, scheduling, and execution, are now clear to me. Additionally, I'm more comfortable reading and editing multithreaded code.
I still need additional experience, though, with more complex subjects like synchronization and managing shared resources. I think I can grasp things at a higher level with more practice and experience.
[Rate yourself and explain: Beginner / Intermediate / Confident]

[Explain your rating - what do you understand well? What needs more practice?]

---

### Feedback on the assignment
This assignment was very helpful in understanding how scheduling algorithms work in practice. It allowed me to apply theoretical concepts in a real coding scenario, which made learning more meaningful. 
Although it was a bit challenging, it improved my problem-solving and debugging skills. I believe this type of assignment is very effective for learning operating systems concepts.
[Any comments about the assignment? Was it helpful? Too easy/hard? Suggestions for improvement?]
