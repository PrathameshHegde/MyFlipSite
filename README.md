# FlipSite Premium Editorial Starter

React + Vite starter for FlipSite: premium editorial layout, responsive book grid, genre filters, search, saved books and a reader-preview modal.

## Windows CMD
```cmd
npm install
npm run dev
```
Open the local URL printed by Vite (usually http://localhost:5173/).

Notes:
- Uses sample book data and remote sample cover images.
- Saved books and progress metadata are stored in localStorage.
- The reader modal is a placeholder, not a working PDF reader.
- `react-pageflip` is included for the next implementation phase.


## Interactive reader demo
Open any book card to try the 12-page sample reader. Page position is saved in localStorage per book and restored when reopened. The included text is placeholder demo content, not the complete publication. This is a frontend prototype; it does not yet load authorized PDFs or provide a secure backend.
