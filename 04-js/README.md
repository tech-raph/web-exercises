# Will Song

## Covered content

- The browser console
- `alert`
- `console.log`
- Function calls: the name, the parentheses, and the argument
- Why the parentheses matter
- Variables with `let`
- Constants with `const`
- Types: string, number, and boolean
- `typeof`
- Adding numbers and assembling strings
- Mixing a number with a string
- Assignment

## Exercises

Work in the browser console. When you are done, write your answers in a new file on a new branch and open a pull request. Leave that pull request open. Use the git cheat sheet from the last exercise for the git commands.

### Try the two functions

- [ ] In Chrome, press Ctrl+Shift+I and open the Console tab. This is a place to type JavaScript and see a result right away.
- [ ] Run `alert("Hello")`. Close the popup before you continue. The page waited until you closed it.
- [ ] Run `console.log("Hello")`. The message appears in the console, and the page does not stop.
- [ ] Look at the two lines. Note what they have in common. You will write that answer in the file at the end.

### A function call

- [ ] Run `console.log("Hello")` again. It runs.
- [ ] Type `console.log` with no parentheses and press Enter. JavaScript shows you the function and does not run it.
- [ ] In the line that ran, point to the three parts: the name, the parentheses, and the value inside. The name is the function. The parentheses mean "run it now." The value inside is the input, called an argument.

### let and const

- [ ] Create a variable: `let message = "Hello"`
- [ ] Print it: `console.log(message)`
- [ ] Point that same name at a new value: `message = "Goodbye"`
- [ ] Print `message` again. The value changed. `let` can be reassigned.
- [ ] Create a constant: `const name = "Will"`
- [ ] Print it: `console.log(name)`
- [ ] Try to point `name` at a new value. Read the error. `const` cannot be reassigned.
- [ ] `let` and `const` both hold a value. Keep this error in mind. You will explain why `const` is still worth using.

### Types

- [ ] Refresh the page and open the console again, so the earlier names are gone.
- [ ] Create a string: `const text = "Hello"`
- [ ] Create a number: `const count = 3`
- [ ] Create a boolean: `const ready = true`
- [ ] Print each one with `console.log`. The string is in quotes. The number has no quotes. The boolean is only `true` or `false`.
- [ ] Ask for the type of each one: `typeof(text)`, `typeof(count)`, and `typeof(ready)`.
- [ ] `typeof` reports the type of the value in the parentheses. The reports are `"string"`, `"number"`, and `"boolean"`.

### Adding and assembling

- [ ] Refresh the page and open the console again.
- [ ] Type `3 + 4` and press Enter. Then type `typeof(3 + 4)`. The value is `7`, and the type report is `"number"`.
- [ ] Type `"Hello" + " " + "Will"` and press Enter. Then type `typeof("Hello" + " " + "Will")`. The `+` sign joined the pieces of text, and the type report is `"string"`.
- [ ] Create two constants: `const first = "Will"` and `const last = "Song"`.
- [ ] Type `first + " " + last` and press Enter. Then type `typeof(first + " " + last)` and write down both results.
- [ ] Type `typeof(3)` and press Enter. Then type `typeof("3")` and press Enter. The values look alike. The reports do not. Write both reports down.
- [ ] Create `const visits = 3` and `const visitsLabel = "3"`.
- [ ] Run `typeof` on each of these and write down the value and the type report. The exercise does not tell you the answers.
  - `visits + 1`
  - `visitsLabel + 1`
  - `3 + 3`
  - `"3" + "3"`
  - `3 + "3"`
  - `"3" + 3`
- [ ] Two of the last four lines have a number in them and still report `"string"`. Mark which ones.

### Assignment

- [ ] Refresh the page and open the console again.
- [ ] Create a variable: `let count = 1`
- [ ] Put a new value in that name: `count = 2`
- [ ] Print `count`. It holds `2`. The single equals sign puts the value on the right into the name on the left. This is not a comparison.

### Open a pull request with your answers

- [ ] In your project folder, create a branch named `js-day-1` and switch to it.
- [ ] Open Notepad for a new file named `answers.md`.
- [ ] In that file, answer the questions at the bottom of this exercise. Put each question as a heading and write your answer under it. Save the file and close Notepad.
- [ ] Stage `answers.md` and commit. Write a short comment that says what this commit adds.
- [ ] Push the `js-day-1` branch to GitHub and open a pull request into `main`.
- [ ] Do not click Merge. Leave the pull request open.
- [ ] Copy the pull request link and send it to me.

## Questions you should be able to answer at this point

Write these answers in `answers.md` on the `js-day-1` branch. That file is what the pull request is for.

- What do `alert` and `console.log` have in common, and how do they behave differently?
- In a function call, what is the name, what do the parentheses mean, and what is the argument?
- What happens when you type `console.log` with no parentheses?
- What is a variable?
- What can you do with `let` that you cannot do with `const`? What did the console say when you tried?
- `let` and `const` can both hold a value. What is the point of using `const`?
- What is a string, a number, and a boolean? What did `typeof` report for each of yours?
- What does `typeof(3)` report, and what does `typeof("3")` report?
- What does `+` do with two numbers? What does it do with two strings? For `visits + 1`, `visitsLabel + 1`, `3 + "3"`, and `"3" + 3`, write the value and the `typeof` report. Which ones came back as `"string"`, and why?
- What does a single equals sign do? What did `count` hold after you assigned `2` to it?
