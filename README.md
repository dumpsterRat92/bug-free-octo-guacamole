# Book Search Engine - MERN Stack with GraphQL

## Description

This application is a Book Search Engine built using the MERN stack (MongoDB, Express.js, React, Node.js). Originally created with a RESTful API, the application has been refactored to use a GraphQL API with Apollo Server. The app allows users to search for books using the Google Books API, save their favorite books, and manage their saved books. 

## User Story

As an avid reader, I want to search for new books to read so that I can keep a list of books to purchase.

## Acceptance Criteria

- **Search Engine**: When the search engine is loaded, the user is presented with a menu with the options "Search for Books" and "Login/Signup", an input field to search for books, and a submit button.
- **Search for Books**: When the user clicks on the "Search for Books" menu option, they are presented with an input field to search for books and a submit button.
- **Search Results**: If the user is not logged in and enters a search term in the input field and clicks the submit button, they are presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site.
- **Login/Signup Modal**: When the user clicks on the "Login/Signup" menu option, a modal appears with a toggle between the option to log in or sign up.
- **Signup**: When the toggle is set to "Signup", the user is presented with three inputs for a username, an email address, and a password, and a signup button. If the user enters valid information and clicks the signup button, their account is created, and they are logged in.
- **Login**: When the toggle is set to "Login", the user is presented with two inputs for an email address and a password, and a login button. If the user enters valid information and clicks the login button, the modal closes, and they are logged in.
- **Logged-in Menu**: When the user is logged in, the menu options change to "Search for Books", "My Saved Books", and "Logout".
- **Save Books**: When the user is logged in and enters a search term, they are presented with search results, each featuring a book’s title, author, description, image, a link to the book on the Google Books site, and a button to save the book to their account. Clicking the save button saves the book to the user’s account.
- **View Saved Books**: When the user clicks on "My Saved Books", they are presented with all the books they have saved to their account, each featuring the book’s title, author, description, image, a link to the book on the Google Books site, and a button to remove the book from their account. Clicking the remove button deletes the book from the saved books list.
- **Logout**: When the user clicks the "Logout" button, they are logged out of the site and presented with a menu with the options "Search for Books" and "Login/Signup", an input field to search for books, and a submit button.

## Technologies Used
- MongoDB: Database for storing user and book information.
- Express.js: Server framework.
- React: Front-end library.
- Node.js: JavaScript runtime.
- GraphQL: API query language.
- Apollo Server: GraphQL server.
- Google Books API: External API for fetching book data.
- Render: Deployment platform.
## Features
- Book Search: Search for books using the Google Books API.
- User Authentication: Sign up and log in using JWT.
- Save Books: Save favorite books to the user’s account.
- View Saved Books: View and manage saved books.
## Deployment
The application is deployed on Render. Make sure to configure the deployment settings on Render, including environment variables and build scripts.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
