# Will Song

## Covered content

- Introduction to HTML
- Tags
- Attributes
- Inner HTML (the content inside a tag)
- PowerShell
- Command line navigation
- Git commands: `git status`, `git add`, `git commit`, `git log`, `git revert`, `git push`

## Exercises

Work in your project folder. Put the new page in the same folder as the first HTML page so the two links can use each other's file names.

- [ ] Open PowerShell.
- [ ] Navigate to the project folder using command line navigation.
- [ ] Confirm you are in the right place: print the current path, then list the files in that folder.
- [ ] From PowerShell, open Notepad for the new page before you write it. Run `notepad` plus the file name, for example `notepad about.html`.
- [ ] Write the second HTML page in that Notepad window, then save the file and close Notepad.
- [ ] Add a link on the new page that goes to the first page, and a link on the first page that comes back to the new page.
- [ ] Open the pages in a browser and make sure navigation works back and forth.
- [ ] Run `git status` and notice that the new page is not staged yet.
- [ ] Add the new page to the staged changes using `git add`.
- [ ] Run `git status` again and confirm the new page is staged.
- [ ] Commit the new page. Git opens a text editor for the commit message. Press `i` to enter insert mode, then write a short comment that says what this commit adds.
- [ ] Save the commit: press Escape to leave insert mode, type `:wq`, and press Enter.
- [ ] Check the history of the repo using `git log`.
- [ ] Copy the latest commit id from `git log` (the one at the top).
- [ ] Run `git revert` with that commit id: `git revert <commit-id>`. The editor opens again. Press `i` if you want to change the message, then Escape and `:wq` to finish.
- [ ] Push the changes to your public repo.
- [ ] Open your repo on GitHub and look at what happened. Share the link with me, and say what changed.

## Questions you should be able to answer at this point

- What is an HTML tag, and what is an attribute?
- What does “inner HTML” mean?
- How do you change folders in PowerShell, and how do you check which folder you are in?
- What does `git status` show you that `git log` does not?
- What is the difference between `git add` and `git commit`?
- In the commit editor, what do `i`, Escape, and `:wq` each do?
- Where do you find a commit id, and which one is the latest?
- What does `git revert` do to that commit, and what did you see on GitHub after you pushed?
