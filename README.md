
# Movie Application Backend with MongoDB

This project is a backend application for a movie management system, implemented in Java using Maven as the build tool and MongoDB as the database. The application provides endpoints to manage movies, such as adding, updating, deleting, and retrieving movie information.

## Prerequisites

Before running this application, ensure you have the following installed:

- Java Development Kit (JDK)
- Apache Maven
- MongoDB Server

## Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/movie-application.git
   ```

2. **Configure MongoDB:**
   - Make sure MongoDB is installed and running on your local machine or update the database connection settings in `src/main/resources/application.properties` file according to your MongoDB server configuration.

3. **Build the Project:**
   ```bash
   cd movie-application
   mvn clean install
   ```

## Usage

1. **Run the Application:**
   ```bash
   java -jar target/movie-application.jar
   ```

2. **Accessing Endpoints:**
   - The application exposes RESTful endpoints to interact with movie data. You can find the API documentation and usage examples in the [API Documentation](#api-documentation) section below.

## API Documentation

- **GET /movies**: Retrieve all movies.
- **GET /movies/{id}**: Retrieve a movie by ID.
- **POST /movies**: Add a new movie.
- **PUT /movies/{id}**: Update an existing movie.
- **DELETE /movies/{id}**: Delete a movie by ID.

For detailed information on request and response formats, refer to the Swagger documentation or API documentation provided by your application.

## Contributing

Contributions are welcome! If you find any bugs or want to enhance the functionality, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For any inquiries or feedback, please contact [MikeJeba](mailto:jebajovitha@gmail.com).

---
