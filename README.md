# Repo for learning git concepts

## How to done task

### _Step-by-step instructions_

1. Open your command line interface or terminal.

2. Navigate to the directory where you want to create the "new-project" directory.

3. Create a new directory called "new-project" using the following command:

   `mkdir new-project`

4. Change to the "new-project" directory using the following command:

   `cd new-project`

5. Initialize a new public Git repository inside the "new-project" directory by running the following command:

   `git init`

6. Create a new file named "README.md" and add the initial text to it using the following command:

   `touch README.md`

   This creates an empty file called README.md. Open the file in a text editor and add your initial text.

7. Prepare the file "README.md" for the commit by running the following command:

   `git add README.md`

   This stages the file for commit.

8. Commit the changes to the repository with the "init" message using the following command:

   `git commit -m "init"`

9. Create a new branch named "development" and move to it using the following command:

   `git checkout -b development`

   This creates a new branch called "development" and switches to it.

10. Add instructions to the "README.md" file and prepare them for the commit by running the following command:

    `git add README.md`

11. Commit the changes in the "development" branch with a commit message using the following command:

    `git commit -m "Add instructions to README.md"`

12. Merge the changes from the "development" branch into the "main" branch using the following command:

    `git checkout main`

    This switches to the "main" branch.

    `git merge development`

    This merges the changes from the "development" branch into the "main" branch.

13. Check the status, make sure everything is up to date, and commit the changes using the following commands:

    `git status`

    This shows the status of the repository.

    `git add .`

    This stages any changes that have not been staged.

    `git commit -m "Merge changes from development branch into main branch"`

    This commits the changes to the repository.

That's it! You have successfully created a new directory, initialized a Git repository, added files to the repository, created and merged a new branch, and committed the changes to the repository.
