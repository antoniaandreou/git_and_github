|Git Command|Description|Example/Note|Enhanced Examples|
|-----------------|----------------|----------------|----------------|
|git config --global user.name "Your Name"|Set up the name for the user when first installing git|-|-|##
|git config --global user.email email@address.com|Set up the email of the user when first installing git|-|-|##
|git config --list|To list all the configurations for the user|-|-|##
|git init| To initialise a repository on a folder|-|-|##
|git status| Check the status of the repository OR if a repository was even initialised yet on that location|-|-|##
|git log|Retrieves information, a log of all the commits for a given repository|:warning: Use **q** to exit the log output|-|##
|git add|Stage changes prior committing. Can group files together so they are under the same commit| git add file.py|git add file_1.py file_2.md file_3.json|##
|git add **.**| Stages all available changes at once, by using the fullspot **.**|-|-|##
|git commit|It will commit all staged changes. You will get prompt to enter a commit message|-|-|##
|git commit **-m "my message"**|Commits staged changes with the given commit message. Prompt avoided|-|-|##
|git commit **--amend**|Opens the latest commit to include forgotten files or change the commit message|:warning: Only works for the latest commit, not any other commit prior that|-|##
|git push **-u origin branch_name**|Pushes a local branch to the remote|Note: **-u** is the short form for --set-upstream|-|##
|git switch **branch_name**|Switches to the specified branch|-|-|##
|git branch|Lists all the available branches|-|-|##
|git branch **branch_name**|Creates a branch with the given name|-|-|##
|git branch **-d branch_name**|Delete the specified branch from the local repository|-|-|##
|git branch --set-upstream-to=origin/<branch> main|If your local branch is not attached to a remote one, you can set tracking information for it by executing this command and specifying the <remote branch>|-|-|##
|git branch -m _old_name_ _new_name_|Rename branch from the name given in _old_name_ to the name given in the _new_name_|_git branch feature/my-branch feature/my-new-branch_|-|##
|git fetch origin **branch_name**|Brings the remote branches into the local|Then run _git checkout **branch_name**_|-|##
|git rebase origin/main|Updates the branch selected with the latest version of the main|Note: First use git switch to the branch you want to rebase|-|##
|git merge **branch_name**|Merges your current branch to the branch you are calling in the command|Current Branch: Develop. Executing _git merge main_ will effectively put develop into main|-|##
|git reset --hard HEAD~1|Use to revert the current branch to a different point in time|If you local is ahead of your remote and you need to align it you can use this command|-|##
|git reset --soft HEAD~1|It will remove the last local (unpushed) commit, but will keep changes you have done.|-|-|##
|git config pull.rebase true|Rebase before doing a pull request|-|-|##
---


