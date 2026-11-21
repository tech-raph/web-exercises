# Will Song

## Covered content

- Command line folder navigation: print the current folder, list files, move into a folder, move up one folder
- Git commands from last time: `git status`, `git add`, `git commit`, `git log`, `git revert`, `git push`
- `git branch`
- `git checkout`
- `git merge`
- Opening a pull request

## Exercises

Work in your project folder. The commands are in the cheat sheet next to this file. First you will move around in PowerShell. Then you will make a small practice change on a branch, merge it, and revert it. After that you will write your answers in a new file on a second branch and open a pull request. Leave that pull request open.

### Move around the folders

- [ ] Open PowerShell.
- [ ] Print the folder you are in.
- [ ] List the files in that folder.
- [ ] Go to your project folder. If you are not sure of the full path, move one folder at a time.
- [ ] Print the folder and list the files again. You should see your HTML files.
- [ ] Move up to the parent folder.
- [ ] Print the folder and list the files so you can see what sits next to the project folder.
- [ ] Move back into the project folder.
- [ ] Print the folder one more time and confirm you are inside the project.

### Practice a branch, a merge, and a revert

- [ ] Check which branch you are on, and which files have changed.
- [ ] Look at the commit history. Note the latest commit, the one at the top, then leave the history.
- [ ] List the branches. The star marks the branch you are on. That branch is usually `main`. The steps below call it `main`. If your star is on a different name, use that name wherever these steps say `main`.
- [ ] Create a branch named `practice` without switching to it.
- [ ] List the branches again. You should see `practice`, and the star should still be on `main`.
- [ ] Switch to `practice`.
- [ ] List the branches. The star should be on `practice` now.
- [ ] From PowerShell, open Notepad for a new file named `practice.txt`.
- [ ] Type one sentence, save the file, and close Notepad.
- [ ] Check the changed files and notice that `practice.txt` is not staged yet.
- [ ] Stage `practice.txt`.
- [ ] Check the changed files again and confirm it is staged.
- [ ] Commit. Git opens a text editor for the commit message. Write a short comment that says what this commit adds, then save the commit and close the editor.
- [ ] Look at the history and confirm the new commit is at the top. Leave the history when you are done.
- [ ] Switch back to `main`.
- [ ] List the files. `practice.txt` is not in the folder. The commit stayed on `practice`.
- [ ] Merge `practice` into `main`.
- [ ] Git should print `Fast-forward`. The merge is already finished, so no editor opens this time.
- [ ] List the files. `practice.txt` is back. Look at the history and confirm the practice commit is now on `main`. Leave the history when you are done.
- [ ] Copy the latest commit id from the history (the one at the top).
- [ ] Revert that commit. The editor opens again. Change the message if you want, then save and close the editor.
- [ ] List the files. `practice.txt` is gone again. Look at the history and you should see the revert commit on top. Leave the history when you are done.
- [ ] Push `main` so GitHub matches your machine before you start the pull request.

### Open a pull request with your answers

- [ ] Create a second branch named `answers`.
- [ ] Switch to `answers`.
- [ ] List the branches and confirm the star is on `answers`.
- [ ] From PowerShell, open Notepad for a new file named `answers.md`.
- [ ] In that file, answer the questions at the bottom of this exercise. Put each question as a heading and write your answer under it. Save the file and close Notepad.
- [ ] Check the changed files and notice that `answers.md` is not staged yet.
- [ ] Stage `answers.md`.
- [ ] Check the changed files again and confirm it is staged.
- [ ] Commit. Git opens a text editor for the commit message. Write a short comment that says what this commit adds, then save the commit and close the editor.
- [ ] Look at the history and confirm the new commit is on `answers`. Leave the history when you are done.
- [ ] Push the `answers` branch to GitHub and link it so later pushes from this branch go to the same place.
- [ ] Open your repo on GitHub. If a banner says **Compare & pull request**, click it. Otherwise open **Pull requests**, then **New pull request**.
- [ ] Set the base branch to `main` and the compare branch to `answers`. The page should show `answers.md` as the change.
- [ ] Write a title and one or two sentences about what the branch adds, then create the pull request.
- [ ] Do not click Merge. Leave the pull request open.
- [ ] Copy the pull request link and send it to me.

## Questions you should be able to answer at this point

Write these answers in `answers.md` on the `answers` branch. That file is what the pull request is for.

- How do you print your current folder, list the files in it, move into a folder, and move up to the parent folder?
- What does `git status` show you that `git log` does not?
- What is the difference between `git add` and `git commit`?
- In the commit editor, what do `i`, Escape, and `:wq` each do?
- What does `git branch` do, and what does `git checkout` do? How do you know which branch you are on?
- Why was `practice.txt` missing after you switched back to `main`, and what did `git merge` do?
- What did `git revert` do to the practice commit, and what did the folder look like afterward?
- What is a pull request? Which branch did you open it from, which branch does it propose to update, and how is that different from `git push`?
