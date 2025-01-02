# backend-beginner-dicoding

Bookshelf API is a simple RESTful API for managing a collection of books. This project was created as part of the **"Belajar Back-End Pemula dengan JavaScript"** course from Dicoding.

**Important Note**: 
While this project is a great starting point, remember that simply copying the work is not enough. It’s crucial to take the time to understand each piece of code, how it works, and why it is structured this way. This will help you build a solid foundation for your skills in backend development. **Learning is about understanding the logic, not just repeating the code.**

## Features
- Add a new book.
- View all books in the collection.
- Retrieve details of a specific book by its ID.
- Update an existing book's details by its ID.
- Delete a book from the collection by its ID.

## Technology Stack
- **Node.js**: JavaScript runtime environment.
- **Hapi.js**: Framework for building the server.
- **NanoID**: For generating unique IDs for books.

## Project Structure
```plaintext
📦bookshelf-api  
 ┣ 📂src                  
 ┃ ┣ 📜bookshelf.js       # Stores book data in-memory.  
 ┃ ┣ 📜handler.js         # Contains the logic for each route.  
 ┃ ┣ 📜routes.js          # Defines all API routes and their handlers.  
 ┃ ┣ 📜server.js          # Entry point for initializing the server.  
 ┣ 📜.gitignore            # Git ignore configuration.  
 ┣ 📜package.json          # Project dependencies and scripts.  
 ┣ 📂api                   # Postman collection and environment for testing.  
 ┃ ┣ 📜Bookshelf API Test.postman_collection.json   # Postman collection for testing API endpoints.  
 ┃ ┣ 📜Bookshelf API Test.postman_environment.json   # Postman environment variables.  
 ┣ 📜README.md             # Project documentation.  
```

## Testing
You can test the API using the provided Postman collection and environment files available in the /api folder. Make sure to import them into Postman to easily test all the endpoints.


