# Notes WebApp

## Overview

This is a simple notes web application built using Flask. It allows users to create, view, edit, and delete notes.

## Features

- Create a new note
- View existing notes
- Edit a note
- Delete a note
- User authentication (signup and login)

## Requirements

- Python 3.12.1
- Flask
- SQLite (or any other database of your choice)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/notes-webapp.git
    cd notes-webapp
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

4. Set up the database:
    ```sh
    flask db init
    flask db migrate -m "Initial migration."
    flask db upgrade
    ```

5. Run the application:
    ```sh
    flask run
    ```

6. Open your browser and navigate to:
    ```
    http://127.0.0.1:5000/
    ```

## Usage

- **Home**: View all your notes.
- **New Note**: Create a new note by clicking on the "New Note" button.
- **Edit Note**: Edit an existing note by clicking the "Edit" button next to the note.
- **Delete Note**: Delete a note by clicking the "Delete" button next to the note.

## Contributing

1. Fork the repository.
2. Create a new branch: `git checkout -b my-feature-branch`
3. Make your changes and commit them: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-feature-branch`
5. Submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
"# Flask Note-Taking App" 
