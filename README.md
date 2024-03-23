# lilygenesis Web App

This is a Flask web application that allows users to search for books and retrieve their details, including the name of the author, file type, download link, and book name, from Library Genesis using the libgen-api.

## Introduction

Library Genesis is a website that provides free access to millions of research articles and books. This web application provides a convenient way for users to search for books and obtain detailed information about them.

## Features

- Web-based interface accessible from any browser.
- Search for books by title, author, or ISBN.
- Retrieve detailed information about books including author name, file type, download link, and book name.
- Display search results in a table format for easy readability.

## Requirements

- Python 3.x
- Flask (`pip install Flask`)
- libgen-api (`pip install libgen-api`)

## Installation

1. Install the required dependencies:

    ```
    pip install -r requirements.txt
    ```

## Usage

1. Navigate to the directory where you cloned the repository:

    ```
    cd library-genesis-book-url-fetcher-webapp
    ```

2. Run the Flask application:

    ```
    python app.py
    ```

3. Open your web browser and go to `http://localhost:5000`.
4. Enter the book title, author, in the search bar and click on the "Search" button.
5. The search results will be displayed in a table format, showing the author name, file type, download link, and book name.


## Acknowledgments

- [Library Genesis](http://libgen.rs/)
- [libgen-api](https://pypi.org/project/libgen-api/)
- [Flask](https://flask.palletsprojects.com/)
