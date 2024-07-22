# Note Taker

## Description

The Note Taker application allows users to write, save, and delete notes. This application uses an Express.js back end and saves and retrieves note data from a JSON file.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [API Routes](#api-routes)
- [Contributing](#contributing)
- [License](#license)

## Installation

To get a local copy up and running, follow these simple steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Ethan-Robertson/Note-Taker.git

Usage

To start the server and use the application locally, run:

bash

npm start

Open your browser and navigate to http://localhost:3000 to view the application.
User Story

AS A small business owner
I WANT to be able to write and save notes
SO THAT I can organize my thoughts and keep track of tasks I need to complete
Acceptance Criteria

    When the Note Taker is opened, the user is presented with a landing page with a link to a notes page.
    When the user clicks on the link to the notes page, they are presented with a page with existing notes listed in the left-hand column, plus empty fields to enter a new note title and the note's text in the right-hand column.
    When the user enters a new note title and the note's text, a "Save Note" button appears.
    When the user clicks the "Save Note" button, the new note is saved and appears in the left-hand column with the other existing notes.
    When the user clicks on an existing note in the list, that note appears in the right-hand column.
    When the user clicks on the "New Note" button, they are presented with empty fields to enter a new note title and the note's text.

Mock-Up

The following animation shows the web application's appearance and functionality:

API Routes

The application includes the following API routes:

    GET /api/notes - Reads the db.json file and returns all saved notes as JSON.
    POST /api/notes - Receives a new note to save on the request body, adds it to the db.json file, and returns the new note to the client.

Deployment

This application is deployed on Render. To access the live application, visit: Note Taker on Render
Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

    Fork the Project
    Create your Feature Branch (git checkout -b feature/AmazingFeature)
    Commit your Changes (git commit -m 'Add some AmazingFeature')
    Push to the Branch (git push origin feature/AmazingFeature)
    Open a Pull Request

License

Distributed under the MIT License. See LICENSE for more information.
Contact

Ethan Robertson - your-email@example.com

Project Link: https://github.com/Ethan-Robertson/Note-Taker