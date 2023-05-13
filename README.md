# express-Local_Library
# Local Library Project

This is a web application for managing a local library, built using Express.js, MongoDB, Pug, JavaScript, and CSS.

## Project Overview

The Local Library project is designed to provide a user-friendly interface for library administrators to manage books, authors, genres, and book copies. It allows users to view the library's collection, search for books, and check the availability of copies.

## Features

1. **Book Management**: Add, edit, and delete books with details such as title, author, summary, genre, and ISBN.
2. **Author Management**: Manage authors by adding their name, date of birth, date of death (if applicable), and a brief bio.
3. **Genre Management**: Create and manage genres to categorize books based on their subject.
4. **Book Copies**: Keep track of the number of copies available for each book and manage their status (available, borrowed, etc.).
5. **Search Functionality**: Enable users to search for books by title, author, genre, or keywords.

## Installation

To run the Local Library project on your local machine, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/Sanoy24/express-Local_Library.git
   ```
2. Navigate to the project directory:
   ```
   cd local-library
   ```
3. Install the dependencies:
   ```
   npm install
   ```
4. Set up the MongoDB connection:
   - Make sure MongoDB is installed and running on your machine.
   - Create a `.env` file in the project root directory.
   - Add the following line to the `.env` file:
     ```
     MONGODB_URI=mongodb://localhost:3000/express-Local_Library
     ```
5. Run the tutorial server, using the appropriate command line shell for your environment:

   ```bash
   # Linux terminal
   DEBUG=express-locallibrary-tutorial:* npm run devstart
   
   # Windows Powershell
   $ENV:DEBUG = "express-locallibrary-tutorial:*"; npm start
   ```
6. Open your web browser and visit `http://localhost:3000` to access the Local Library application.

## Technologies Used

- [Express.js](https://expressjs.com/): A fast, unopinionated web framework for Node.js.
- [MongoDB](https://www.mongodb.com/): A popular NoSQL database for storing and retrieving data.
- [Pug](https://pugjs.org/): A template engine for generating dynamic HTML.
- JavaScript: The programming language used for client-side interactivity.
- CSS: Cascading Style Sheets for styling the user interface.

## Contributing

Contributions to the Local Library project are welcome! If you have any bug reports, feature requests, or improvements, please submit them as issues or pull requests to this repository.


## Acknowledgements

The Local Library project is based on the [MDN Local Library tutorial](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Tutorial_local_library_website). Special thanks to the Mozilla Developer Network (MDN) for providing the foundation of this project.

## Contact

For any inquiries or questions, feel free to contact the project maintainer:

- Name: Yonas Mekonnen
- Email: myonas886@gmail.com

Enjoy managing your local library with this web application!
