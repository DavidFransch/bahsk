# SafariFlow AI — prototype

This is a clickable prototype of SafariFlow AI.
It helps a safari lodge's reservations team answer guest enquiries.
It is not a real product. Nothing is saved. All lodges, guests and numbers are made up.

Raylin designed it. The first version in the history is her original file, unchanged.

## Look at it

**Online:** https://davidfransch.github.io/bahsk/

**On your computer:**

1. Download the files. On GitHub, click the green **Code** button, then **Download ZIP**.
2. Unzip the folder.
3. Double-click `index.html`. It opens in your web browser.

You do not need to install anything.

## What is in this folder

| File | What it is |
|---|---|
| `index.html` | The whole prototype. Design, wording and demo data all live here. |
| `content/templates.md` | Reply templates. The master copy of reply wording. |
| `content/faq.md` | Knowledge base questions and answers. The master copy. |
| `decisions.md` | Choices we have made, with the date and the reason. |
| `TODO.md` | Things we know need changing. |
| `designs/` | Screenshots and design files. See `designs/README.md` for how to name them. |

## Where to edit things

Everything is in `index.html`. It has clear headings to help you find your way.
Use your browser's search (Ctrl+F on Windows, Cmd+F on Mac) to jump to them.

### Colours, fonts and spacing

Search for: `DESIGN TOKENS`

You will see lines like `--green:#1f4a3a;`. The part after the colon is the colour.
Change the colour code. Keep the semicolon at the end.

### Wording

Search for: `CONTENT —`

All the words on screen live here: headings, button labels, enquiry examples, the draft reply, knowledge base answers.
Change the words between the quote marks. Keep the quote marks and the commas.

If your text contains an apostrophe, like `we'd`, wrap it in double quotes: `"we'd like"`.

### Demo numbers, bookings and lodge details

Search for: `DEMO DATA`

This holds the fake lodge name, bookings, invoices, the availability calendar and all the figures.
None of it is real.

### Reply templates and FAQ

The files in `content/` are the master copy.
When you change a reply or an answer:

1. Change it in `content/templates.md` or `content/faq.md`.
2. Make the same change in `index.html`, in the `CONTENT` section.
   Each part of the markdown file tells you where it lives.

Nothing copies these across automatically. You have to do both.

## Setup mode

The product comes in two versions.

- **Layer** — the lodge already has its own booking system. We sit on top of it. Bookings, Invoices and Reports are hidden.
- **Full** — the lodge has no system. Everything is shown.

**To switch while you look:** use the **Setup mode** switch in the left sidebar.

**To change which one it opens in:** search `index.html` for `SETUP_MODE`.
Change `'layer'` to `'full'`, or back. Keep the quote marks.

## Make a change on GitHub (no installing)

1. Open the repository on github.com.
2. Click the file you want to change, for example `index.html`.
3. Click the pencil icon (top right of the file). This opens the editor.
4. Make your change.
5. Click the green **Commit changes…** button.
6. Write a short message saying what you changed. For example: "Reword the draft reply".
7. Leave **Commit directly to the main branch** selected. Click **Commit changes**.

The live site updates within a few minutes.

If you are pasting a change from an AI tool, paste only the part it tells you to replace.
Then open the live site and check it still works.

**If something breaks:** every change is saved in the history.
Tell David. Any earlier version can be brought back.

## About the live site

The online link uses GitHub Pages.
For now this repository is public, so anyone with the link can see it. Pages is free for public repositories.
If we make it private later, Pages will need a paid GitHub plan (Pro, Team or Enterprise).
