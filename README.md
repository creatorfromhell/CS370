# Project Two: Reinforcement Learning Treasure Hunt

## Project Reflection

### What code were you given? What code did you create yourself?

In this project, I was provided with a foundational implementation of a reinforcement learning-based maze environment, which included the core structure of the Qmaze class, the Experience replay mechanism, and the neural network model architecture for training. These components established a working environment for simulating and learning from agent actions within a maze-based treasure hunt scenario.

The core logic I developed involved orchestrating the training loop across multiple epochs. This included initializing the agent in a random free cell, executing game episodes until win/loss conditions were met, and integrating the decision-making mechanism using either exploration or exploitation strategies. Specifically, I implemented the per-epoch loop where the agent chooses an action based on E-greedy strategy, steps through the environment, stores transitions into the experience buffer, and trains the neural network based on sampled experiences. I also tracked win/loss metrics and monitored win rate over time to assess training success.

---

### What do computer scientists do and why does it matter?

Computer scientists analyze complex problems, design algorithms, and develop scalable software systems to solve real-world challenges. In the context of artificial intelligence and machine learning, they craft intelligent agents that can learn from experience, adapt behavior, and automate tasks that would otherwise require human decision-making. This work is critical because it underpins innovations across healthcare, finance, robotics, cybersecurity, and more—transforming industries and improving quality of life globally.

---

### How do I approach a problem as a computer scientist?

My approach to problem-solving begins with understanding the requirements and breaking the task into manageable components. For this project, I analyzed the maze environment and identified how agent decisions influenced outcomes. From there, I applied principles of reinforcement learning, used appropriate data structures for memory (experience replay), and implemented a training loop that refined the agent’s behavior over time. I iteratively tested, tweaked hyperparameters (like E and batch size), and analyzed win rates to evaluate model performance. This modular and iterative approach helped me isolate problems, apply known strategies, and measure progress effectively.

---

### What are my ethical responsibilities to the end user and the organization?

As a computer scientist, I recognize the importance of building systems that are fair, transparent, and safe. In AI applications like this one, ethical responsibility includes ensuring that models learn in unbiased ways and that results are interpretable and reliable. For end users, I must prioritize usability, accuracy, and respect for privacy. For organizations, I have a duty to write maintainable, secure, and efficient code that aligns with broader goals and compliance standards. As AI becomes increasingly integrated into decision-making systems, it's essential to build trust through responsible design and clear communication about limitations and risks.

---

## Final Thoughts

Through this project, I gained hands-on experience with reinforcement learning and deepened my understanding of how agents can learn from interaction with environments. The project brought together many concepts from this course—including neural networks, reward-driven learning, and data processing—and reinforced the importance of ethical and methodical development in AI. This work forms a strong addition to my portfolio, both as a technical accomplishment and as a reflection of my growth as a computer scientist.
