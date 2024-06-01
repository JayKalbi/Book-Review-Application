# Book-Review-Server-Side-Application
### Course Information
Title: Developing Back-End Apps with Node.js and Express
Type: Final Project
Course Provider: IBM

### Technologies Used
The project leverages the Express server to seamlessly incorporate CRUD functionalities via HTTP methods, tested efficiently with Postman. Emphasizing security, Session and JWT authentication are integrated to ensure only authenticated users can perform specific operations. The code is optimized using Promises, Callbacks, or Async/Await functions, facilitating concurrent interactions by multiple users without dependencies on each other's operations.

### Features
- Retrieve a list of all books available in the bookshop: Users can view a comprehensive list of all available books.
- Search for specific books: Users can search for and retrieve details of books based on ISBN code, author names, and titles.
- Retrieve reviews/comments for specified books: Users can view all reviews or comments associated with a particular book.
- Register as a new user: New users can register to gain access to additional features.
- Login to the application: Registered users can log in to access their account and additional features.
- Add a new review for a book: Logged-in users can add reviews for books.
- Modify a book review: Logged-in users can modify only their own reviews.
- Delete a book review: Logged-in users can delete only their own reviews.
- Concurrent User Access: Multiple users can access the application simultaneously to view and manage different book reviews.

### Getting Started

Clone or Download the Repository:

#### Clone the repository to your local machine using:

-- git clone https://github.com/your-username/Book-Review-Server-Side-Application.git

Alternatively, download the ZIP file from the repository page and extract it to your desired location.

#### Install Dependencies:

##### Navigate to the project directory and run:

-- npm install

##### Configure Environment Variables:

Create a .env file in the root directory and add necessary environment variables such as database connection strings, JWT secret, etc.

##### Run the Application:

Start the server by running:

-- npm start

The application will be accessible at http://localhost:5000.

##### Test the Application:

Use Postman or a similar tool to test the endpoints and functionalities of the application.

##### Explore the Codebase:

Review the code to understand the structure and implementation of the Book Review Server-side Application.

### Contact

For any issues or inquiries, please contact:

Name: Jay Kalbi

Email: jdkalbi18@gmail.com

GitHub: https://github.com/JayKalbi
