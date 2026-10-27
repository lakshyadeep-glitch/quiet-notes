<p align="center">
  <img src="Glossy%20Quill%20and%20Notepad%20Icon.png" alt="Quiet Notes Logo" width="180">
</p>

<h1 align="center">Quiet Notes</h1>

<p align="center">
  A calm, lightweight, browser-based note-taking app for focused writing.
</p>

<p align="center">
  <a href="https://lakshyadeep-glitch.github.io/quiet-notes/">Live Demo</a>
</p>

Overview
Quiet Notes is a minimal note-taking application designed to help you capture ideas, write notes in Markdown, and keep important information organized. It runs directly in your browser and stores notes locally on your device.
Features
- Create and Delete Notes: Create notes whenever you need them and delete notes you no longer want.
- Instant Search: Search note titles and content.
- Markdown Editor: Write using Markdown, including headings, lists, blockquotes, inline code, code blocks, and links.
- Live Markdown Preview: Switch between writing and rendered preview.
- Automatic Saving: Changes are saved to browser local storage.
- Pinned Notes: Pin important notes and filter the list to show pinned notes.
- Light and Dark Themes: Switch between light and dark appearance.
- Export a Note: Download an individual note as a Markdown (.md) file.
- Export a Backup: Export the notes library as a JSON file for backup.
- Word and Character Counts: See the current note's word and character count.
- Last Edited Timestamps: See when notes were last updated.
- Keyboard Shortcuts: Use Ctrl/⌘ + N to create a note and Ctrl/⌘ + S to save.
- Responsive Layout: Use the app on desktop and mobile screens.
Live Demo
Try Quiet Notes here:

Open Quiet Notes
The live demo will show the upgraded version only after the updated app is deployed to GitHub Pages.

Technologies Used
- HTML5 — application structure
- CSS3 — styling, responsive layout, and themes
- JavaScript — note management and interface interactions
- Web Storage API (localStorage) — local persistence
- Blob and URL APIs — downloading notes and backups
No external libraries or build tools are required.
Getting Started
You can use Quiet Notes through the live demo or run it locally.
Run Locally
1. Clone the repository:
   git clone https://github.com/lakshyadeep-glitch/quiet-notes.git
2. Open the project folder.
3. Open index.html in your browser.
No additional dependencies or installation are required.
Deploy the Updated Version
To publish the upgraded app at the existing GitHub Pages URL:
1. Download or open the upgraded HTML file.
2. Rename it to index.html.
3. Replace the old index.html in your repository with the upgraded version.
4. Commit and push the changes to GitHub.
5. Wait for GitHub Pages to finish deploying, then open the live demo.
Keep Glossy Quill and Notepad Icon.png in the repository root so the logo image continues to work.
Data Storage and Privacy
Quiet Notes stores notes in the browser's local storage.
- Notes remain in the browser and device where they were created.
- Notes are not automatically synchronized between devices or browsers.
- Clearing browser site data may delete saved notes.
- Export a JSON backup regularly if your notes are important.
The JSON export is a backup file; it does not automatically restore or import notes into the app.
Keyboard Shortcuts
Shortcut	Action
Ctrl + N / ⌘ + N	Create a new note
Ctrl + S / ⌘ + S	Save the current note
↑ / ↓	Navigate notes when focus is in the notes list
Esc	Clear the search field when it is focused


Project Structure
quiet-notes/
├── Glossy Quill and Notepad Icon.png
├── README.md
└── index.html
Future Improvements
Possible future additions include:
- Importing and restoring JSON backups
- Folders and tags for organizing notes
- More Markdown features and formatting tools
- Optional synchronization across devices
License
No license has been specified for this project yet.
Made with care by Lakshya :)
