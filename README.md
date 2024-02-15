# Movie CRUD App using GoLang and REST API
This repository contains a simple CRUD (Create, Read, Update, Delete) application for managing movies using GoLang for the backend and a REST API.

-> Features
Create: Add new movies to the database.
Read: Retrieve a list of all movies or a specific movie by ID.
Update: Modify existing movie details.
Delete: Remove a movie from the database.

-> Technologies Used
GoLang: Backend language for handling server logic and database operations.
Gorilla Mux: Router for mapping HTTP requests to the corresponding handler.
JSON: Data interchange format used for communication between client and server.
REST API: Follows Representational State Transfer principles for interaction between systems.
CORS Middleware: Cross-Origin Resource Sharing middleware for enabling communication with different origins.
Static File Server: Serves static HTML files for frontend interaction.

-> Usage
Clone the repository to your local machine.
Ensure you have GoLang installed.
Navigate to the project directory.
Run the following command to start the server:
go run main.go
Access the application through a web browser or API testing tool.

->API Endpoints
GET /movies: Retrieve a list of all movies.
GET /movies/{id}: Retrieve a specific movie by ID.
POST /movies: Add a new movie to the database.
PUT /movies/{id}: Update an existing movie.
DELETE /movies/{id}: Delete a movie from the database.

->Static Files
Static HTML, CSS, and JavaScript files are served from the static directory.
Access the frontend interface by navigating to the root URL (/) in a web browser.
