# Fullstack Developer Assignment
**Objective: This assignment aims to assess your fullstack development skills. This will simulate a basic library management system. You will build both the backend (PHP with Symfony) and frontend (React) functionalities.**

### Functionality:
* Users can login to the system. (Basic authentication with a fixed credential provided for testing)
* Users can view a list of available books. (20 sample data entries should be enough and the data source can be taken from the [OpenLibrary.org](https://openlibrary.org/collections/greatbooks))
* Each book has a title and author.
* Users can search for books by title and author.
* The system should display appropriate messages (success, error) for user actions.

### Requirements/prerequisites:
* Frontend: React
* Backend: PHP with Symfony framework
* Database: MySQL (or any equivalent)

### Part 1: Database Schema Design (~1 hour)
1. Design a simple database schema for the library management system with tables for users and books.

### Part 2: Backend (PHP with Symfony) (~2 hours)
1. Create a minimal Symfony project.
2. Implement basic user login functionalities for at least 2 test users. (Consider using a library like Symfony Security)
3. Define models for User and Book entities.
4. Implement functionalities to:
* List all available books
* Search for books by title or author (using SQL or a query builder)
5. Implement API endpoints for the functionalities mentioned above.

### Part 3: Frontend (React) (~1 hour)
1. Create a simple React application to display a list of available books and a search bar.
2. Develop a component to display a list of books with title and author information, and implement pagination to show 10 books at one load.
3. Implement a basic search bar to filter books by title using React state.
4. Display appropriate messages for successful or failed searches.

### Testing:
* Focus on manual testing of the functionalities for basic functionality.

### Notes:
* Focus on clean code practices and basic documentation for both backend and frontend.
* This is a sample assignment, and the focus should be on demonstrating core concepts and building a functional application within the approximate timeframe.
* Feel free to use additional libraries or tools as needed, but document them in your README file.

**Once completed, submit it to your GitHub account, including the SQL export file for the DB schema and sample data and provide us with the repository link. Also include a README file with instructions on how to run your application (setup, dependencies).**

## Have fun!
