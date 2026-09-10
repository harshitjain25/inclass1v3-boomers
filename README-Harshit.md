# inclass1v3-boomers

# In-Class 1 v3 — Harshit Jain

## Personal Reflection

### 1. What surprised you most about how the widget tree, state, or lifecycle actually behaves once you saw it applied in the app?

What surprised me most was how much structure is behind a screen that looks simple. In my previous In-Class 01b tabs app, the Scaffold contained the AppBar, TabBar, TabBarView, and BottomAppBar, and each tab had its own widgets inside it. I understood this better when I looked at the code as a widget tree instead of just looking at the final screen. The TabController also showed me that some parts of the app need state and lifecycle management even though the user only sees the tabs.

### 2. Which concept took the longest to click for you, and what finally made it make sense?

The concept that took the longest to click for me was Stateless versus Stateful widgets. At first, I mainly thought of a stateful widget as something that was interactive. Looking back at my In-Class 01b code helped me understand it better. The tab screen needs state because it uses a TabController and manages changing information, while MyApp does not need to keep track of changing data. Seeing how `initState()`, the controller, and `dispose()` were connected made the difference clearer.

### 3. What part of the GitHub workflow felt least familiar, and how did you work through it?

The GitHub collaboration workflow was the least familiar part because the previous tabs work was done individually. Today I had to work with a shared repository, clone it, set my Git identity, and create my own branch instead of simply working on my own project. I also had to understand how the local repository connects to GitHub. I worked through it by checking the output of each Git command and following the workflow step by step rather than trying to do everything at once.

### 4. If you rebuilt this activity from scratch tomorrow, what would you do differently?

If I did this activity again tomorrow, I would set up the shared GitHub repository and branch workflow first and make sure I understood who was responsible for each part. Since the earlier Flutter coding was individual, the biggest difference today was learning how to coordinate changes with another person. I would also communicate with my teammate before making changes so we know what each person is working on and can avoid unnecessary confusion.

## Peer Feedback

### 5. What specific contribution from your teammate did you find genuinely helpful, and why?

My teammate worked on Questions 3 and 4 of critical thinking, created his own README file, and reviewed my work. His review was helpful because I got another person's perspective before finishing my answers.

### 6. What constructive feedback could help your teammate collaborate even more effectively next time?

I think we could communicate a little more while working, especially about what each of us has finished. That would make the teamwork feel more organized.

### 7. What is one thing you learned from watching how your teammate approached a problem?

I learned that having someone else review your work can help you notice things you might miss when working alone.

### 8. How did the two of you resolve any disagreements or merge conflicts, and what would you try differently next time?

We didn't have any major disagreements or merge conflicts. We reviewed each other's work and worked through the assignment without any major issues.