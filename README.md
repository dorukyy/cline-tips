# Cline Tips

# Introduction

Cline is a popular tool among developers and non-developers alike, designed to streamline software creation, maintenance, and development. This guide provides essential tips, best practices, and troubleshooting strategies to help you maximize your use of Cline.

# Tips & Tricks

## Models
- Anthropic: Claude 3.5 Sonnet [Link](https://openrouter.ai/anthropic/claude-3.5-sonnet)
- DeepSeek V3 [Link](https://openrouter.ai/deepseek/deepseek-chat)
- Qwen2.5 Coder 32B Instruct [Link](https://openrouter.ai/qwen/qwen-2.5-coder-32b-instruct)

1. Use .clinerules

Creating a .clinerules file can improve the accuracy of the responses you receive and help reduce costs. This file acts as a guide for Cline, defining rules and configurations for your project.

2. Choose the Right Model

For simple tasks: Use cheaper and faster models.

For complex tasks: Opt for more expensive and accurate models.

Balancing cost and performance is key. Using the most expensive models for every task can significantly increase expenses without proportional benefits.

3. Specify Your Tech Stack

When starting a project from scratch, clearly define the technologies you intend to use. This avoids misunderstandings and ensures a solid project structure.

Example:

```
I have X project...

Tech stack is:
    - language: Python
    - database = mysql
    - library_x
    - library_y
```


By specifying these upfront, you enable Cline to build a cohesive project structure in one go.

4. Optimize Your Prompts

Provide detailed and precise instructions for better results. Avoid vague prompts like:

```
Build me a to-do list app
```

Instead, include specifics such as:

```
I need X bot developed in Python with SQLite. 

Key requirements:

    - Users can do x
    - Users can't do x without y 

Tech stack is:
    - language: Python
    - database = mysql
    - library_x
    - library_y

Notes:

1. Focus on dynamic architecture
2. Clean interfaces
3. Optimal performance
4. Use design patterns
5. Follow clean code principles
6. Separation of concerns
7. Modular and testable code
8. Ensure scalability for future growth
9. Use commends when needed

```



This ensures higher-quality outputs that align with your expectations.

5. Don’t Expect Perfection

Remember that Cline is a tool, not a replacement for human expertise. Relying on it entirely can be costly and impractical. Validate critical code, especially for payment modules or sensitive systems.

6. Resolve Infinite Loops

Sometimes, Cline may get stuck in a loop trying to resolve an error. In such cases:

Open a new chat and rephrase the issue.

Share relevant links or solutions you’ve found.

Your involvement can expedite the resolution process.

7. Always Review the Code

Cline is not infallible. Regularly review its outputs to ensure accuracy and reliability, particularly in critical parts of your project.


## Note Taking

### TODO List Management

Creating a cline_todo.md file allows you to track tasks effectively. Once a task is complete, Cline can mark it as done automatically, helping you stay organized.


Example usage in .clinerules

```
- Create a `cline_todo.md` file to track tasks. When a task is received, the agent should document the following in the file:
  - Task description: A clear summary of the task to be performed.
  - Timestamp: The exact date and time when the task came in.
  
- Break down complex tasks into smaller subtasks. Each subtask should be listed with:
  - Action to be taken: A specific instruction or step to perform.
  - Dependencies or prerequisites: Any conditions that must be met before starting the task.
  - Status: Update the status to "In-progress," "Completed," or "Blocked."

- Whenever a change occurs (e.g., progress or obstacles), update the file:
  - Completion date for each subtask.
  - Notes on progress, any blockers, or additional insights.

- Use a consistent format in each entry to ensure clarity:
  - Task received: [Date & Time]
  - Action: [Detailed description]
  - Status: [In-progress / Completed / Blocked]
  - Notes: [Any additional comments or blockers]

- The agent must maintain the file in an organized manner, updating it in real-time and ensuring all changes are reflected immediately.
```

### Change Tracking

Cline’s changes can be stored in a dedicated file for better performance and version control. This is especially useful in collaborative environments or large projects.

Example usage in .clinerules
```
- Create a `cline_changes.md` file to store all changes made within the project. Record the following:
  - Date & Time: When the change occurred.
  - Action: A description of the change made (e.g., update, bug fix, new feature).
  - Reason: Why the change was necessary or implemented.
  
- For each change:
  - Track which components were affected.
  - Note the person/team responsible for the change.
  - Update the file as new changes are made, ensuring that the history remains clear.

- Use a consistent format:
  - Change recorded: [Date & Time]
  - Action: [Description]
  - Affected components: [List of impacted areas]
  - Reason: [Why the change was necessary]
  - Notes: [Additional details or remarks]
```


# External Links

- [cline-memory-bank.md](https://github.com/nickbaumann98/cline_docs/blob/main/prompting/custom%20instructions%20library/cline-memory-bank.md) - nickbaumann98/cline_docs  
- [ClaudeAI subreddit](https://www.reddit.com/r/ClaudeAI/)  
- [ChatGPT Coding subreddit](https://www.reddit.com/r/ChatGPTCoding/)
- [Open Router](https://openrouter.ai/)
- [Roo Cline (Cline Fork)](https://github.com/RooVetGit/Roo-Cline)

# Final Thoughts

Cline is a powerful AI assistant for software development. When used effectively, it can save time, reduce costs, and enhance productivity. By following this guide and continuously refining your approach, you can unlock Cline’s full potential.

# Contributions
This repository is dedicated to providing comprehensive guides and documentation. If you’d like to contribute:

Add new guides or update existing ones with relevant, clear, and concise information.
Ensure that your contributions align with the overall purpose and style of the repository.
Submit your changes through a pull request with a clear description of your addition or update.
We appreciate your help in making this repository a valuable resource for everyone!
