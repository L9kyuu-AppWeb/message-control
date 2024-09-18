# message-control
Memudahkan untuk copy text message saat mau ngirim pesan pake template
# Message Control Application

This is a simple web-based application that allows users to create, edit, and manage custom text notes. Users can copy the content of these notes, edit them, and delete them easily. The application supports exporting and importing data in JSON format and provides a user-friendly interface using **Tailwind CSS** and **SweetAlert2** for enhanced notifications.

## Features

- **Create Notes**: Add custom titles and text notes, with optional background colors.
- **Copy Notes**: Easily copy text to the clipboard with a notification powered by SweetAlert2.
- **Edit Notes**: Modify existing notes.
- **Delete Notes**: Remove notes from the list.
- **Export/Import**: Export the notes to a JSON file or import notes from an external JSON file.
- **Responsive Design**: The interface is fully responsive and adjusts to different screen sizes.

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/message-control-app.git
   cd message-control-app
   Open the index.html file in your preferred browser to view and use the application.

Dependencies
The application uses the following libraries and frameworks:

Tailwind CSS: A utility-first CSS framework for styling.
Font Awesome: For icons used in the user interface.
SweetAlert2: For displaying notifications (e.g., when copying text).
The necessary libraries are loaded from CDNs, so no additional installation is needed.

Usage
Add a New Note
Enter a title in the "Judul" field.
Enter the content of your note in the text area.
Optionally, select a background color from the dropdown menu.
Click the "Simpan Perubahan" button to add the note.
Copy a Note
Click the copy icon next to a note.
A notification will appear indicating that the text has been successfully copied to your clipboard.
Edit a Note
Click the edit icon next to the note you wish to modify.
The note’s title and content will be loaded into the input fields.
Make your changes and click "Simpan Perubahan" to save them.
Delete a Note
Click the trash icon next to the note you wish to delete.
The note will be removed from the list.
Export Notes
Click the "Ekspor Data" button to download a JSON file containing all your notes.
Import Notes
Click the "Impor Data" button and select a JSON file containing previously exported notes.
License
This project is licensed under the MIT License - see the LICENSE file for details.

© l9kyuu 2024
