# Git and commands
DevOps Git Section

# Git
Stages in GIT.

"Working area/untracked area"

"Staging area/tracked area"

"Local repository"

# Git Username and Email

"git config --global --list" ----> to list which email username is connected.

"git config --global --unset user.name" ----> to remove the connected username.

"git config --global --unset user.email" ----> to remove the connected email.

"git config --global user.name RanjeethAcharya" ----> to connect the GitHub username.

"git config --global user.email EXAMPLE@gmail.com" ----> to connect the GitHub email.

# Git Init, Status, Add, and Commit

"git init" ----> initializes a new Git repository in the current directory.

"git status" ----> displays the current state of the working directory and the staging area.

"git add file.txt" ----> means you are adding the file file.txt to the staging area, preparing it to be included in the next commit.

"git commit -m "the file is updated" " ----> creates a new commit with the staged changes and includes the message "the file is updated" as the commit message. This message describes the changes made in this commit.

# Git history of commits

"git log --oneline" ----> git will show all commit messages. 

# Git Branch

"git branch" ----> will show all existing lists of branches.

"git branch master" ----> will make a new branch name of the master.

"git checkout master" ----> switches to a branch named master.

"git checkout -b master" ----> -b creates and switches to a new branch named master.

"git push --set-upstream origin master" or "git push -u origin master" ----> will add new branch in GitHub repository

# Git Push and Pull

"git push origin" ----> It will push all files into the given repository.





