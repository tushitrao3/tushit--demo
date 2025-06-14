# tushit--demo
This is my first git repository
 Experiment Steps:
 Step 1: Setting Up Git Repository
 ● Openthecommand-line interface on your computer.
 ● Navigate to the directory where you want to create your Git repository.
 ● Runthefollowing commands:
 git init
 ● Thisinitialises a new Git repository in the current directory.
 Step 2: Creating and Committing Changes
 ● Create a new text file named "example.txt" using any text editor.
 ● Addsomecontent to the "example.txt" file.
 ● Inthe command-line interface, run the following commands:
 5
git status
 ● This command shows the status of your working directory, highlighting untracked
 files.
 git add example.txt
 ● Thisstages the changes of the "example.txt" file for commit.
 git commit-m "Add content to example.txt"
 ● Thiscommits the staged changes with a descriptive message.
 Step 3: Exploring History
 Modify the content of "example.txt."
 Run the following commands:
 git status
 ● Notice the modified file is shown as "modified."
 git diff
 ● Thisdisplays the differences between the working directory and the last commit.
 git log
 ● Thisdisplays a chronological history of commits.
 Step 4: Branching and Merging
 Create a new branch named "feature" and switch to it:
 git branch feature
 git checkout feature
 or shorthand:
 git checkout-b feature
 ● Makechanges to the "example.txt" file in the "feature" branch.
 ● Commit the changes in the "feature" branch.
 ● Switch back to the "master" branch:
 git checkout master
 ● Mergethe changes from the "feature" branch into the "master" branch:
 git merge feature
 Step 5: Collaborating with Remote Repositories
 ● Create an account on a Git hosting service like GitHub (https://github.com/).
 ● Create a new repository on GitHub.
 6
● Linkyour local repository to the remote repository:
 git remote add origin <repository_url>
 ● Pushyour local commits to the remote repository:
 git push origin master
 Conclusion:
 Through this experiment, participants gained a foundational understanding of 
