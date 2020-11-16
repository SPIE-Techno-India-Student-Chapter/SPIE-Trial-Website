# SPIE-Trial-Website

# Git Usages

# Branching

1. git checkout -b <branch_name> [creates a new branch, and checks out into it]
2. git branch [list out available/existing branches]
3. git branch <branch_name> [creates a new branch only]
4. git checkout <branch_name> [checks out into an existing branch]
2. git push -u origin <branch_name> [pushes the branch to the github repo]

# Cloning

1. git clone --branch <branch_name> url [clones all the branches and checks-out into the specific branch <branch_name>]
2. git clone url[clones only main/master branch]


# Merging
1. git merge <branch_name> [merges the branch <branch_name> with the main branch]
2. git checkout branch1 [to checkout to branch1 from main branch]
3. git merge origin/branch2 [to merge the contents of branch2 with branch1]

# Points to Remember
1. Committed changes will remain in one branch and the other branches won't have the changes but all the changes will show in git Desktop.
2. Changes in one branch won't show up in the other branches unless we merge it with that particular branch.
3. While editing a file if we change the branch without committing the changes to the previous branch the changes will show up in later branch and if there we commit the changes that will remain in the later branch. So its recommended to commit the changes made in one branch before checking out in other branch.
