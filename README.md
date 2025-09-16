A Colleague's Guide to Git and GitHub
This repository is designed to help our team get comfortable with Git and GitHub. We'll cover the essential commands and concepts you'll use daily to collaborate on projects.

1. What is Git?
Git is a version control system. Think of it as a powerful "save" button for your code. It tracks changes to files over time, allowing multiple people to work on the same project without overwriting each other's work. It also lets you revert to previous versions if something goes wrong.

2. What is GitHub?
GitHub is a cloud-based hosting service for Git repositories. It provides a user-friendly interface to manage your projects, collaborate with others, and showcase your work. It's essentially social media for code.

3. The Core Workflow
This is the basic flow you'll use for most of your work.

Clone: Copy a repository from GitHub to your local machine.

git clone [repository URL]

Make changes: Edit, add, or delete files in your local repository.

Add: Stage your changes. This tells Git which files to include in the next commit.

git add . (stages all changes) or git add [file name]

Commit: Save your staged changes to your local history with a descriptive message.

git commit -m "Brief message about your changes"

Push: Upload your local commits to the remote repository on GitHub.

git push

Pull: Download changes from the remote repository to update your local copy. It's good practice to pull before you push to avoid conflicts.

git pull

4. Branches 🌿
A branch is a separate line of development. The main branch is typically called main or master. You'll create a new branch for each new feature or bug fix you work on. This keeps the main codebase stable.

Create a new branch and switch to it: git checkout -b [your-branch-name]

Switch between branches: git checkout [branch-name]

Merge your branch: Once your work is complete, you'll open a Pull Request on GitHub to merge your changes back into the main branch.

5. Getting Help
For quick tips: Refer to this README.

For specific commands: git help [command]

For hands-on help: Don't hesitate to ask a colleague for a walkthrough. We're all learning together!
