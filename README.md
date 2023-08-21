## Blog Project Documentation

### Overview

The Blog Project is a React application that allows users to create, read, update, and delete blog posts. It utilizes a JSON server as a backend to store and retrieve blog data.

### Prerequisites

Before getting started, ensure that you have the following prerequisites:

1. Node.js and NPM (Node Package Manager) installed on your machine.
2. A text editor or IDE of your choice, such as Visual Studio Code.

### Installation

To set up the project, follow these steps:

1. Clone the project repository from GitHub.

git clone https://github.com/Jahsil/eyus-blog.git

2. Navigate to the project directory.

cd eyus-blog

3. Install the required dependencies using NPM.

npm install

### Running the Application

To run the application, follow these steps:

1. Start the JSON server.

npx json-server --watch src/data/db.json --port 8000

The JSON server will run on `http://localhost:8000/blogs`.

2. In a separate terminal, start the React development server.

npm run dev

The React application will open in your default web browser at `http://localhost:5173`.

### Usage

The Blog Project offers the following functionality:

1. **View Blog Posts**: The homepage displays a list of all blog posts. Clicking on a post will take you to its details page.

2. **Create a Blog Post**: Click on the "Create" button on the navbar to create a new blog post. Fill in the required fields (such as title, content, and author) and submit the form.

3. **Delete a Blog Post**: On the details page of a blog post, click the "Delete" button to remove the post permanently.

### Technologies Used

The Blog Project utilizes the following technologies:

- React - JavaScript library for building user interfaces.
- JSON server - Lightweight backend for storing and retrieving blog data.

### Conclusion

The Blog Project is a React application that demonstrates CRUD operations on a JSON server, allowing users to create, read, and delete blog posts.
