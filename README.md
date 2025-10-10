# Technical Writing Assignment

For guidance on setting up and submitting this assignment, refer to the Marcy lab School Docs How-To guide for [Working with Short Response and Coding Assignments](https://marcylabschool.gitbook.io/marcy-lab-school-docs/how-tos/working-with-assignments#how-to-work-on-assignments).

## Prompt 1

A good technical explanation often uses a metaphor to help others understand a complex concept. Choose a metaphor to represent a Git commit. 

In a few brief paragraphs, use your chosen metaphor to explain:
* What a commit is
* How a commit is created (include the command-line syntax)
* Why commits are useful in version control.
* Why it is important to write descriptive clear messages in team settings.

### Response 1
# What is a commit?
1. A commit is a way to **save the most recent changes** in your GitHub Repository. After it has been added with `git add` and staged using `git commit` , the commit will save these changes and provide a message of what was updated. 
This process allows you to keep track of your project over time. Once the newest changes are **staged** Developers commit the updates they **want** to commit `git push`. Usually the best improvement or version as they move along in the project.

We can think of a commit as an *analogy* like taking a picture or a snapshot of your project 📸. It's a way for us to capture what our work looked like in that exact moment.

# How do we create a commit and use the commands?
After coding and your file is ready to go. It is now time to save these changes! 

1. It is best to always make sure you are inside of the correct folder before saving. Once in the right folder, inside your terminal                                           
**Type:** `git add - A` + `Enter`. This adds your changes.

2. **Type:** `git commit -m" "` + `Enter` to stage your most recent changes. Here you'll want to provide a comment inside the quotations to explain what your changes are. This will be the time to decide and look over what changes you want to push up to GitHub.

3. Finally the final step! 

   When you have staged and confirmed your finished product/changes it is time to push them up. **Type:** `git push` to push up changes to GitHub.

   This pushes your commits to GitHub so your changes show up online.

4. You can check **GitHub** afterward to confirm it went through. It usually shows something like **“updated X minutes ago”** next to your file name or commit message — that means GitHub received your latest version!

# Why are commits useful in version control?

Commits are useful in version control because they act like **save points** in your project’s history. They make it easy to track progress and refer back to previous versions if something breaks. Commits also give you the freedom to collaborate with others without overwriting their changes. Plus, you can create new branches to test ideas safely and merge them only when they work.

# Why is it important to write descriptive, clear messages in team settings?

It’s important to write clean, organized code so your program works properly and is easy to read. Clear commit messages and code comments help your team understand what each change does and why it was made. This makes collaboration smoother, allows others to edit or build on your work confidently, and helps everyone stay on the same page about your project’s functionality.