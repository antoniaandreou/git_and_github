|Git Command|Description|Example/Note|Enhanced Examples|
|-----------------|----------------|----------------|----------------|
|git init| To initialise a repository on a folder|-|-|##
|git status| Check the status of the repository OR if a repository was even initialised yet on that location|-|-|##
|git log|Retrieves information, a log of all the commits for a given repository|:warning: Use **q** to exit the log output|-|##
|git add|Stage changes prior committing. Can group files together so they are under the same commit| git add file.py|git add file_1.py file_2.md file_3.json|##
|git add **.**| Stages all available changes at once, by using the fullspot **.**|-|-|##
|git commit|It will commit all staged changes. You will get prompt to enter a commit message|-|-|##
|git commit **-m "my message"**|Commits staged changes with the given commit message. Prompt avoided|-|-|##
|git commit **--amend**|Opens the latest commit to include forgotten files or change the commit message|:warning: Only works for the latest commit, not any other commit prior that|-|##
|git switch **branch_name**|Switches to the specified branch|-|-|##
|git push **-u origin branch_name**|Pushes a local branch to the report| Note: **-u** is the short form for --set-upstream|-|##
|git branch|Lists all the available branches|-|-|##
|git branch **branch_name**|Creates a branch with the given name|-|-|##
|git branch **-d branch_name**|Delete the specified branch from the local repository|-|-|##
|git fetch|Brings the remote branches into the local|-|-|##
|git rebase origin/main|Updates the branch selected with the latest version of the main| Note: First use git switch to the branch you want to rebase|-|##
|git branch --set-upstream-to=origin/<branch> main|If your local branch is not attached to a remote one, you can set tracking information for it by executing this command and specifying the <remote branch>|-|-|##
|git merge **branch_name**| Merges your current branch to the branch you are calling in the command| Current Branch: Develop. Executing _git merge main_ will effectively put develop into main|-|##
---


