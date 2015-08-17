# Git-Training
This is a repository for training others to use Git and GitHub

## Instructions

1. Visit https://github.com/JacobAMason/Git-Training and flick the Fork
button to fork this GitHub repository.

2. Create a local copy of your fork of the repository using the following command:

        git clone https://github.com/<your username>/Git-Training

3. Using your favorite text editor, add a new file to this repository.

    a) Make the name of the file your first name, then a hyphen, then a random
       number, for example `jacob-3486`.
    b) In this file, you can tell us a bit about yourself, for example:

       I am a student at Mississippi State University and I enjoy programming in Python.

4. Commit this addition to your fork of the repository using the following commands:

        git add <name of file>
        git commit -m "Added my open source interests."

5. Push your changes to the remote repository with the following command:

        git push

6. Visit the GitHub page for your fork of the repository, e.g.:

        https://github.com/<your GitHub username>/Git-Training

 Observe that your file is visible in the GitHub web view for the repository.

7. Click the green button to create a pull request for your changes. This will
take you to a page where you can review your diff and commit message. Click the
green "Create Pull Request" button, leave a comment, and click the green "Send
pull request button".

8. The owner of the project, JacobAMason, can now review and merge your pull
request.

9. Update your fork of the project to see everyone else's changes, using the
following command:

        git pull --rebase

10. Explore the changes with commands like `git log` and `git show`.

-
Credit for this exercise goes to Jessica McKellar https://github.com/jesstess/contrib-test
