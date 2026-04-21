# CS-370-Current-Emerging-Trends-in-CS

**Briefly explain the work that you did on this project: What code were you given? What code did you create yourself?**
For this project, I was given a starter Jupyter Notebook that already had the maze environment set up, along with helper classes like the treasure maze and experience replay system. The structure of the project was mostly there, including instructions for where to implement the reinforcement learning logic. The main focus was completing the training portion of the agent rather than building everything from scratch.
The part I created myself was the actual deep Q-learning implementation inside the training loop. I worked on how the agent selects actions, stores experiences, and updates the neural network over time. I also trained the model and monitored things like win rate and loss to see how it improved. After enough training, the agent was able to consistently solve the maze and eventually reached a 100% win rate around epoch 324, which showed that it learned the optimal path instead of just getting lucky.  

**Connect your learning from throughout this course to the larger field of computer science:**

**What do computer scientists do and why does it matter?**
From this course, I’ve learned that computer scientists are basically problem solvers who use technology to build systems that can make decisions and handle complex tasks. It’s not just about writing code—it’s about designing solutions that actually work in different situations and can improve over time. This project was a good example of that because the agent had to learn how to navigate the maze instead of being told exactly what to do.
This matters because these types of systems are used in real-world situations, not just small projects like this. Reinforcement learning can be applied to things like robotics, navigation systems, and even healthcare-related decision making. Being able to design systems that learn and adapt makes a big difference in how efficiently problems can be solved at a larger scale.

**How do I approach a problem as a computer scientist?**
As a computer scientist, I approach a problem by breaking it down into smaller pieces and figuring out a logical way to solve it step by step. Instead of trying to jump straight to the answer, I had to understand how the environment worked, what the agent needed to learn, and how to guide that learning using rewards and penalties.
It also showed me that a lot of problem solving in computer science is iterative. The agent didn’t work right away, it had to go through multiple training cycles before improving. I had to pay attention to things like win rate and performance over time to know if I was actually making progress. That trial-and-error process is a big part of how real-world systems get developed and improved.

**What are my ethical responsibilities to the end user and the organization?**
One of my main responsibilities is making sure that whatever system I build actually works the way it’s supposed to and has been tested properly. Just because something works once doesn’t mean it’s reliable, and this project showed that pretty clearly. The agent needed consistent performance, not just a single successful run.
I also have a responsibility to be honest about what a system can and can’t do. For an organization, that means not overstating results or assuming the model is perfect when it still has limitations. Overall, ethical responsibility in computer science comes down to building systems that are reliable, tested, and transparent so users and organizations can trust the results.
