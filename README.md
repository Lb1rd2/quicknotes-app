# QuickNotes

QuickNotes is a simple note-taking web app. You type a note, choose a category (Personal, Work or Study), and the app shows it as a card. Notes are saved in your browser, so they are still there after you refresh the page.

## Features

- Add notes with a category (Personal, Work or Study)
- Each note shows its text, category label and date and time
- Delete any note
- Search notes by word (not case-sensitive)
- Error messages for empty notes and notes over 200 characters
- Live count of notes
- Notes saved with localStorage
- Responsive layout for phones

## How to run locally

1. Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/quicknotes-app.git
```

2. Open the `quicknotes-app` folder in VS Code.
3. Right-click `index.html` and choose **Open with Live Server**. You can also double-click `index.html` to open it in your browser.

## What I learned

- How to build a page with semantic HTML tags and a form with linked labels and inputs
- How to use Flexbox, category classes and a media query to make a layout work on phones
- How to build the page from an array of objects with `createElement` and `textContent`
- How to save and load data with `localStorage`, `JSON.stringify` and `JSON.parse`
- How to make small Git commits, one for each task
