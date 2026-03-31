# Reflection Questions

## Instructions
Answer the following questions about your learning experience. Each answer should be **at least 5-7 sentences** and show your understanding.

---

## Question 1: What did you learn about multithreading?

**Your Answer:**

I learned how multithreading allows multiple tasks to run concurrently within a program, improving performance and responsiveness. I understood how threads are created in Java using the Runnable interface and how they are started using Thread.start(). I also learned about the thread lifecycle, including states such as running and terminated. Through this assignment, I saw how threads can simulate real CPU scheduling using the Round-Robin algorithm. It helped me understand how processes share CPU time fairly using a time quantum. One interesting part was seeing how threads execute independently but are still controlled by the scheduler. Overall, I gained a practical understanding of how operating systems manage multiple processes efficiently.
---

## Question 2: What was the most challenging part of this assignment?

**Your Answer:**

The most challenging part was understanding how the scheduler controls process execution and how threads interact with each other. It was difficult to track when a process should be re-enqueued and when it should finish execution. Implementing new features without breaking the existing functionality was also challenging. For example, adding priority and context switching required careful placement in the code. Another difficulty was understanding the flow of the program, especially inside the main scheduling loop. These challenges were directly related to understanding core operating system concepts like scheduling and concurrency. Overall, it required both coding skills and strong conceptual understanding.
---

## Question 3: How did you overcome the challenges you faced?

**Your Answer:**

I overcame the challenges by breaking the problem into smaller parts and focusing on one feature at a time. I carefully read the existing code and added comments to understand how each part works. I also tested the program after every change to make sure everything was working correctly. When I faced issues, I used debugging techniques such as printing values and tracking execution flow. I also reviewed lecture materials and searched for examples of Java threading online. Practicing small examples helped me understand the behavior of threads better. This step-by-step approach made the assignment more manageable
---

## Question 4: How can you apply multithreading concepts in real-world applications?

**Your Answer:**

Multithreading is widely used in real-world applications to improve performance and user experience. For example, web browsers use multiple threads to load web pages, images, and scripts at the same time. In mobile applications, threads are used to handle background tasks like data fetching without freezing the user interface. In games, multithreading helps manage graphics, sound, and user input simultaneously. The Round-Robin scheduling concept can be applied to ensure fairness between tasks sharing resources. This assignment helped me understand how these systems manage multiple operations efficiently. It also showed how important threading is in building responsive and scalable applications.

---

## Additional Reflections (Optional)

### What would you like to learn more about?

[Any topics related to threading, concurrency, or operating systems that you're curious about?]

---

### How confident do you feel about multithreading concepts now?

I would rate myself as intermediate. I understand the basic concepts such as thread creation, execution, and scheduling. However, I still need more practice with advanced topics like synchronization and handling complex concurrency issues.

---

### Feedback on the assignment

The assignment was very useful in understanding practical concepts of multithreading. It was slightly challenging but helped me improve both my coding and problem-solving skills. I think it was well-designed because it combined theory with implementation.
