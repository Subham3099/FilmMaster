# Movie CRUD App using GoLang and REST API<br>
This repository contains a simple CRUD (Create, Read, Update, Delete) application for managing movies using GoLang for the backend and a REST API.<br><br>

-> Features<br>
Create: Add new movies to the database.<br>
Read: Retrieve a list of all movies or a specific movie by ID.<br>
Update: Modify existing movie details.<br>
Delete: Remove a movie from the database.<br>

-> Technologies Used<br>
GoLang: Backend language for handling server logic and database operations.<br>
Gorilla Mux: Router for mapping HTTP requests to the corresponding handler.<br>
JSON: Data interchange format used for communication between client and server.<br>
REST API: Follows Representational State Transfer principles for interaction between systems.<br>
CORS Middleware: Cross-Origin Resource Sharing middleware for enabling communication with different origins.<br>
Static File Server: Serves static HTML files for frontend interaction.<br>

-> Usage<br>
Clone the repository to your local machine.<br>
Ensure you have GoLang installed.<br>
Navigate to the project directory.<br>
Run the following command to start the server:<br>
go run main.go<br>
Access the application through a web browser or API testing tool.<br>

->API Endpoints<br>
GET /movies: Retrieve a list of all movies.<br>
GET /movies/{id}: Retrieve a specific movie by ID.<br>
POST /movies: Add a new movie to the database.<br>
PUT /movies/{id}: Update an existing movie.<br>
DELETE /movies/{id}: Delete a movie from the database.<br>

->Static Files<br>
Static HTML, CSS, and JavaScript files are served from the static directory<br>
Access the frontend interface by navigating to the root URL (/) in a web browser.<br>
