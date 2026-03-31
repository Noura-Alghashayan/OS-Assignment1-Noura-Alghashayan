# Development Log

## Instructions
Document your development process as you work on the assignment. Add entries showing:
- What you worked on
- Problems you encountered
- How you solved them
- Time spent

**Requirements**: Minimum 5 entries showing progression over time.

---

## Example Entry Format:

Entry 1 - [April 1, 2026, 2:30 PM]
What I did: Forked the repository and set up my student ID

Details:

Created GitHub account with university email
Forked the starter repository
Changed student ID on line 92 to my actual ID (441234567)
Compiled and ran the program successfully
Challenges: Had to install JDK first because javac wasn't recognized

Solution: Downloaded JDK 17 from Oracle website and set PATH variable

Time spent: 30 minutes 

---

## Your Development Log:

### Entry 1 - [March 28, 2026, 9:30 AM]
**What I did**: Set up the development environment and started the assignment.

**Details**: 
1- Installed Git and connected it to my GitHub account  
2- Opened the project using Visual Studio Code  
3- Prepared the environment to start working  

**Challenges**: Ensuring everything was properly connected between Git, GitHub, and VS Code.

**Solution**: Carefully followed setup steps and verified everything was working correctly.

**Time spent**: 1–1.5 hours

---

### Entry 2 - [March 28, 2026, 10:32 AM]
**What I did**: Set my student ID and verified the initial setup.

**Details**: 
1- Inserted my student ID into the code  
2- Saved and reviewed the changes  
3- Confirmed that the program was ready for further development 

**Challenges**: Making sure the correct student ID was inserted since it affects the simulation output.

**Solution**: Double-checked the value and ensured the file was updated correctly.

**Time spent**: 20–30 minutes 

---

### Entry 3 - [March 28, 2026, 4:47 PM]
**What I did**: Completed Feature 1 (Priority attribute).

**Details**:  
1- Added a priority attribute to each process  
2- Generated random priority values  
3- Displayed priority when processes were added to the ready queue  
4- Verified correctness through program output  

**Challenges**:  
Understanding where to integrate the priority without affecting the scheduling logic.

**Solution**:  
Added the priority during process creation and updated the ready queue display.

**Time spent**: 1.5–2 hours  

---

### Entry 4 - [March 30, 2026, 7:48 AM]
**What I did**: Completed Feature 2 (Context Switch Counter).

**Details**:  
1- Added a counter variable for context switches  
2- Incremented the counter during scheduling  
3- Displayed the total count at the end of execution  
4- Tested the output to ensure accuracy  

**Challenges**:  
Identifying the correct point where a context switch occurs.

**Solution**:  
Analyzed the scheduling loop and updated the counter only when a process was re-queued.

**Time spent**: 1–1.5 hours 

---

### Entry 5 - [March 30, 2026, 7:10 PM]
**What I did**: Completed Feature 3 (Waiting Time Tracking).

**Details**:  
1- Implemented waiting time tracking for each process  
2- Updated waiting time before execution  
3- Stored all processes in a list for final reporting  
4- Displayed a formatted waiting time summary  

**Challenges**:  
Calculating waiting time correctly and ensuring it updates at the right moment.

**Solution**:  
Created a dedicated method to update waiting time and called it before execution.

**Time spent**: 2 hours   

---

### Entry 6 - [March 30, 2026, 9:53 PM]
**What I did**: Completed REFLECTION.md.

**Details**:  
1- Answered all reflection questions in detail  
2- Explained what I learned about multithreading  
3- Described the challenges I faced and how I solved them  
4- Completed the additional reflection section  

**Challenges**:  
Writing detailed answers that clearly reflect my understanding while keeping them aligned with the assignment requirements.

**Solution**:  
Carefully reviewed each question and expanded my answers based on my actual experience during the assignment.

**Time spent**: 1.5-2 hours  

---

### Entry 7 - [March 30, 2026, 11:16 PM]
**What I did**: Completed ANSWERS.md.

**Details**:  
- Answered all four assignment questions  
- Used actual program output as examples  
- Explained scheduling behavior and thread states clearly  
- Completed the summary section  

**Challenges**:  
Ensuring that all answers were clear, well-structured, and supported by my program output.

**Solution**:  
Reviewed my output carefully and adjusted my explanations to match the actual behavior of the program.

**Time spent**: 1 hour


---

## Summary

**Total time spent on assignment**:  10–12 hours across 3 days 

**Most challenging part**:  
The most challenging part was implementing the waiting time tracking correctly without affecting the Round-Robin scheduling logic. It required careful thinking to decide when and where the waiting time should be updated. Ensuring accurate results while keeping the program stable was not straightforward.

**Most interesting learning**:  
The most interesting part was seeing how Round-Robin scheduling works in practice through actual output. Observing how processes move in and out of the ready queue, how context switching happens, and how waiting time accumulates made the concept much clearer than just studying it theoretically.

**What I would do differently next time**:  
Next time, I would continue following the same structured approach I used, while adding a more detailed final review to ensure the accuracy and organization of all outputs.  
