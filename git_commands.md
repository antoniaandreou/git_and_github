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
---


