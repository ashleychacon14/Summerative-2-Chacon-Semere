# Summerative-2-Chacon-Semere
Spring Boot GraphQL Project
This project demonstrates the use of Spring Web, Spring Data JPA, and Spring for GraphQL to build a simple book management system. The system allows for the creation, reading, updating, and deletion of books, authors, and publishers, as well as the searching of books by author ID. The project also includes GraphQL queries for retrieving publishers, authors, and books with their related entities.


# Getting Started
To get started with this project, follow these steps:

1. Clone this repository to your local machine.
2. Open the project in your preferred IDE.
3. Build the project using Maven.
4. Run the project using the main class.

# Code Structure
------------------
# BookController
- Contains the REST endpoints for managing books.
# AuthorController
- Contains the REST endpoints for managing authors.
# PublisherController
- Contains the REST endpoints for managing publishers.
# Book
- Represents a book entity.
# Author
- Represents an author entity.
# Publisher
- Represents a publisher entity.
# BookRepository
- Provides methods for interacting with the book table in the database.
# AuthorRepository
- Provides methods for interacting with the author table in the database.
# PublisherRepository
- Provides methods for interacting with the publisher table in the database.
# BookService and BookServiceImpl
- Provide business logic for managing books.
# AuthorService  and AuthorServiceImpl 
- Provide business logic for managing authors.
# PublisherService and PublisherServiceImpl
- Provide business logic for managing publishers.
# GraphqlController and GraphqlProvider
- Provide the GraphQL endpoint and schema for querying and mutating books, authors, and publishers.





