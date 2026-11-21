# Cheat sheet

Replace `path`, `file`, `name`, and `commit-id` with the real folder, file, branch, or commit id.

## Folders

`pwd`
Prints the folder you are in.

`ls`
Lists the files and folders in the folder you are in.

`cd path`
Moves you into that folder, with quotes around the path if it contains a space.

`cd ..`
Moves you up one folder, into the parent.

`notepad file`
Opens that file in Notepad and creates it if it does not exist yet.

## Git

`git status`
Shows which branch you are on, which files changed, and which of those files are staged.

`git log`
Shows past commits with the newest one at the top.

`q`
Closes the history screen.

`git branch`
Lists the branches and puts a star next to the one you are on.

`git branch name`
Creates a branch with that name and does not switch to it.

`git checkout name`
Switches you to that branch.

`git add file`
Stages that file so the next commit includes it.

`git commit`
Starts a commit of the staged files and opens an editor for the message.

`i`
Lets you type the commit message.

`Escape`
Stops insert mode so the editor will take a command.

`:wq`
Saves the message and closes the editor after you press Enter.

`git merge name`
Brings that branch's commits into the branch you are on.

`git revert commit-id`
Adds a new commit that undoes the commit with that id.

`git push`
Sends the commits on your current branch to GitHub.

`git push -u origin name`
Sends that branch to GitHub and remembers it so the next push updates the same branch.
