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

### Entry 1 - [April 1, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**: 
- Created GitHub account with university email
- Forked the starter repository
- Changed student ID on line 92 to my actual ID (441234567)
- Compiled and ran the program successfully

**Challenges**: Had to install JDK first because javac wasn't recognized

**Solution**: Downloaded JDK 17 from Oracle website and set PATH variable

**Time spent**: 30 minutes

---

## Your Development Log:

### Entry 1 - [April 2, 2026, 3:30 PM]
**What I did** Understood the starter code

**Details**:
 • Reviewed Process class
 • Reviewed SchedulerSimulation class
 • Understood how threads are created and executed
 • Analyzed run() method

**Challenges**: Difficulty understanding thread behavior

**Solution**: Read about Java threads and practiced simple examples

**Time spent**: 2 hours

---

### Entry 2 - [April 3, 2026, 5:30 PM]
**What I did**: Implemented Feature 1 (Process Priority)

**Details**:
 • Added priority field to Process class
 • Generated random priority values
 • Displayed priority in ready queue output

**Challenges**: Output formatting broke initially

**Solution**: Adjusted print statements carefully

**Time spent**: 2.5 hours

---

### Entry 3 - [April 4, 2026, 5:30 PM]
**What I did**: Implemented Feature 2 (Context Switch Counter)

**Details**:
 • Added static counter variable
 • Incremented counter when each process starts
 • Displayed total switches at the end

**Challenges**: Unsure where to update the counter

**Solution**: Placed it before each thread execution

**Time spent**: 2 hours

---

### Entry 4 - [April 5, 2026, 6:30 PM]
**What I did**: Implemented Feature 3 (Waiting Time) and testing

**Details**:
 • Added time tracking using System.currentTimeMillis()
 • Calculated waiting time for each process
 • Displayed summary table
 • Tested full program

**Challenges**: Calculating waiting time correctly

**Solution**: Tracked start and end times for each process

**Time spent**: 3 hours
---

### Entry 5 - [April 6, 2026, 7:30 PM]
**What I did**: Debugging and improving program output

**Details**:
 • Fixed minor bugs in the code
 • Checked output consistency
 • Improved readability of console output
 • Verified all features work together

**Challenges**: Some values were not displaying correctly

**Solution**: Reviewed logic and corrected variable usage

**Time spent**: 2 hours
---

### Entry 6 - [April 8, 2026, 10:30 PM]
**What I did**: Final testing and preparing submission

**Details**:
 • Ran the program multiple times
 • Checked all requirements are completed
 • Reviewed DEVELOPMENT_LOG.md
 • Prepared repository for submission

**Challenges**: Ensuring everything meets assignment requirements

**Solution**: Compared work with assignment instructions and checklist

**Time spent**: 1.5 hours
---

## Summary

**Total time spent on assignment**: 14.5 hours

**Most challenging part**:
Understanding how threads work and how the scheduler controls process execution was the most difficult part. Especially managing when to re-enqueue a process and when it should finish required careful thinking.

**Most interesting learning**:
Learning how multithreading works in Java and seeing how processes are scheduled using Round-Robin was very interesting. It helped me understand how real operating systems manage tasks efficiently.

**What I would do differently next time**:
I would start earlier and spend more time understanding the code before implementing features. I would also test each feature step by step to avoid errors later.
