
#Quora Clone

A simple Quora-like application built using Node.js, Express.js, and EJS templating engine.

#Features

- Create, Read, Update, Delete (CRUD) operations: Users can create new posts, read existing posts, update posts, and delete posts.
- UUID-based post IDs: Each post is assigned a unique ID using the uuid library.
- EJS templating engine: The application uses EJS templating engine to render dynamic HTML templates.
- Method override: The application uses method override to support PUT and DELETE requests.

#Technologies Used

- Node.js: A JavaScript runtime built on Chrome's V8 JavaScript engine.
- Express.js: A popular Node.js web framework.
- EJS: A templating engine that allows you to generate HTML templates with dynamic data.
- UUID: A library for generating unique IDs.

#Getting Started

1. Clone the repository: Clone this repository to your local machine using git clone.
2. Install dependencies: Run npm install to install the required dependencies.
3. Start the application: Run node app.js to start the application.
4. Access the application: Open your web browser and navigate to http://localhost:8080/posts.

#API Endpoints

- GET /posts: Retrieves a list of all posts.
- GET /posts/new: Renders the new post form.
- POST /posts: Creates a new post.
- GET /posts/:id: Retrieves a single post by ID.
- PATCH /posts/:id: Updates a single post by ID.
- DELETE /posts/:id: Deletes a single post by ID.

Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request.

License

This project is licensed under the MIT License. See the LICENSE file for details.
