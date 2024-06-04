# Personal-bookshelf

This project is a React application that allows users to search for books using the Open Library API and maintain a personal bookshelf in the browser using localStorage.

## Features

- **Book Search**: Search for books using the Open Library API.
- **Personal Bookshelf**: Add books to a personal bookshelf stored in localStorage.
- **Responsive UI**: The application is responsive and works well on different screen sizes.

## Setup Instructions

### Prerequisites

Make sure you have the following software installed:

- [Node.js](https://nodejs.org/en/download/) (version 12 or higher)
- [npm](https://www.npmjs.com/get-npm) (usually comes with Node.js)

### Clone the Repository

```sh
git clone https://github.com/your-username/personal-bookshelf.git
cd personal-bookshelf

### Technologies Used :

React
CSS (for styling)
Open Library API
localStorage (for persistent bookshelf storage)

API Reference
The application uses the Open Library API to search for books :"https://openlibrary.org/search.json?q=YOUR_QUERY&limit=10&page=1"

q: Name of the book.
limit: Number of results per page (set to 10).
page: Page number (only the first page is used in this application).
