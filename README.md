# CyberNotes Application

This project is a web-based note-taking application that allows users to create, save, edit, search, and preview notes with Markdown support. The application uses [Dexie.js](https://dexie.org/) for local IndexedDB storage and provides both light and dark themes, which can be toggled by the user.

## Features

- **Create and Edit Notes**: Users can add a title, content, and tags to their notes.
- **Markdown Support**: Users can use Markdown syntax in their notes and toggle between editing and preview modes.
- **Persistent Storage**: Notes are saved locally using IndexedDB, allowing them to persist between sessions.
- **Search Functionality**: Users can search notes by title, content, or tags.
- **Theme Toggle**: Users can switch between light and dark themes, with the theme preference saved to `localStorage`.
- **Auto-Save**: Changes to notes are automatically saved in real-time as users type.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Preview Mode](#preview-mode)
- [Search Functionality](#search-functionality)
- [Theme Toggle](#theme-toggle)
- [Auto-Save](#auto-save)
- [Contributing](#contributing)
- [License](#license)

## Installation

This project runs entirely in the browser and does not require any backend setup. You can clone the repository and open the `index.html` file in your browser to run the app.

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/notes-app.git

	2.	Open the project directory:

cd notes-app


	3.	Open the index.html file in your browser:

open index.html



Dependencies

	•	Dexie.js: A minimal wrapper for IndexedDB to manage the local storage of notes.
	•	Marked.js: A markdown parser and compiler used for rendering Markdown in the preview mode.

You can include these libraries in your project by adding the following <script> tags to your HTML file:

<script src="https://unpkg.com/dexie@latest/dist/dexie.js"></script>
<script src="https://cdn.jsdelivr.net/npm/marked/marked.min.js"></script>

Usage

Adding a New Note

	1.	Click the “New Note” button to clear the current note form.
	2.	Enter a title, content (which supports Markdown), and optional tags (separated by commas).
	3.	Your note will automatically be saved as you type.

Editing an Existing Note

	•	To edit an existing note, click the note title in the note list. The note content will be loaded, and you can modify the title, content, or tags.

Saving Notes

	•	Notes are saved automatically whenever you make changes. No manual save button is required.

Preview Mode

	•	To see a live preview of your note in Markdown format, click the “Preview” button. This will toggle the display between the editor and the rendered Markdown.
	•	The preview is powered by Marked.js.

Search Functionality

	•	You can search notes by title, content, or tags using the search bar. The search results are updated in real-time as you type.

Theme Toggle

	•	You can switch between light and dark themes by clicking the “Toggle Theme” button.
	•	The current theme preference is stored in localStorage and will be applied automatically the next time you open the app.

Auto-Save

	•	The app includes auto-save functionality. Any changes to the note title, content, or tags are automatically saved without the need to manually save.

Contributing

If you’d like to contribute to this project:

	1.	Fork the repository.
	2.	Create a new branch (git checkout -b feature-branch).
	3.	Make your changes.
	4.	Commit your changes (git commit -m 'Add new feature').
	5.	Push to the branch (git push origin feature-branch).
	6.	Open a pull request.

License

This project is licensed under the MIT License. See the LICENSE file for details.

This README is structured to give users clear instructions on how to install and use your note-taking application, with sections explaining the major features like Markdown preview, search, theme toggle, and auto-save. Let me know if you'd like to make any changes!
