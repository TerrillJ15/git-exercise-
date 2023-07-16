# Git Exercise
Author: Jessica Terrill

This repo demonstrates how to use Git.

## Exercise Steps
1. Go to GitHub and create a new Repository. Name it git-exercise and tick the check box for "Initialize this repository with a README".
2. Clone this repository onto your computer using the terminal. Git will ask you for your username and password, use the Personal Access Token as your password.
3. Create a new branch in git, call it "readme".
4. Open up the project folder in Visual Studio Code or your preferred text editor. Do not select "clone repository into VSC", just open the directory by clicking "Open folder", or use the top menu File -> Open.
5. Edit the README.md file with anything you like, something small.
6. Add README.md to staging in Git.
7. Commit your changes with a message.
8. Push your "readme" branch to your git-hub repository.
9. Make a pull request of your "readme" branch to your "main" branch on GitHub.
10. Merge your pull request into "main".
11. Switch back to "main" branch in your local repository.
12. Pull the updates from your GitHub repository to your local "main" branch.
13. List all of your branches locally.
14. Create a new branch and call it develop.
15. Create three files, "index.html", "style.css" and "application.js".
16. Add all three files to your staging.
17. Commit your changes with a message.
18. Push your "develop" branch to GitHub.
19. Switch back to your "readme" branch.
20 Make a small change in your "README.md" file.
21. Repeat step 6 to 12.
22. Switch to your "develop" branch.
23. Rebase your "develop" branch with your "main". ($ git rebase main)
24. Push your "develop" branch onto GitHub. Your push should be rejected, you need to force push this branch, add --force at the end of your push command. Using --force is a simple solution for this scenario since you are the only person editing this branch. But if you are working in a team and there are others working on the same branch, force push can be dangerous and may result in data loss. Check out The dark side of the force push
25. Make a pull request of your develop branch on to main.
26. Merge the pull request.
27. Switch back to your local main branch and pull the updates.
28. Repeat steps 6 - 28 until you are comfortable with this flow.
