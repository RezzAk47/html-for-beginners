# Episode 1 practice: first tags

**Goal:** fix a broken page, then write your own small page, using only h1, p and strong.

## What you need
- A web browser (Chrome or Firefox is fine).
- A plain text editor. You do not have a code editor yet (Episode 2 sets one up). Use what your computer has:
  - Windows: Notepad.
  - Mac: TextEdit. Choose Format, then Make Plain Text, before you type.
  - Linux: any plain text editor that came with your system.
- Paper works for the thinking parts, but you need a file to open in the browser.

## The task
**Part 1: fix `starter/broken.html`**
1. Copy `broken.html` to a new place, such as your Desktop. Keep the original.
2. Open the copy in your text editor and read it line by line.
3. Fix every mistake you find. There are more than three.
4. Open the fixed file in your browser (double click it, or use Open with and pick your browser).

**Part 2: write `about-me.html`**
1. Make a new plain text file named `about-me.html`.
2. Write a page that follows the rules below, then open it in your browser.
   - One `h1` with your name.
   - Two paragraphs under it.
   - The first paragraph has exactly one `strong` word.
   - The second paragraph has exactly two `strong` words.
   - No other tags.

**Part 3: check yourself**
Count your opening tags and your closing tags. The two counts must match.

## Done when
- [ ] `broken.html` shows one heading and three normal paragraphs, with only the right words bold.
- [ ] Every opening tag in `broken.html` has its closing tag.
- [ ] `about-me.html` opens in the browser and shows a heading and two paragraphs.
- [ ] The strong words sit inside the paragraphs, not around them.
- [ ] Your opening and closing tag counts match.

## Hints
<details>
<summary>Hint 1: the page looks wrong, but where is the mistake?</summary>
Browsers try to guess what you meant, so one bad tag can change how far down the page the effect goes. Read the code, not only the page.
</details>

<details>
<summary>Hint 2: how do I find a mistake?</summary>
Take each opening tag and look for its own closing tag. The closing tag has a slash and the same name. Also check which tag was opened last. It must close first.
</details>

<details>
<summary>Hint 3: my file opens as plain text full of tags</summary>
Check the file name. It must end in .html, not .txt. On Windows, in the Save window, set the type to All files. Type the full name, such as about-me.html. On a Mac, if TextEdit asks, choose to use .html.
</details>

## Stretch goal
Put a third `strong` word in the second paragraph. Then, without opening the browser, say what you expect to see.

## Solution
The answer is in [`solution/`](solution/). Try the task first.
