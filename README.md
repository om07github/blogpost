# Blog Post Application

Welcome to the Blog Post Application! This project allows you to create, read, update, and delete blog posts using an API. It is built using Node.js, Express, CSS, and body-parser for server-side handling

## About

This application demonstrates a simple blog post system where users can manage posts. The project uses two main components:
1. **Server (server.js)**: Handles the front-end rendering and interacts with the API to manage blog posts.
2. **API (index.js)**: Provides endpoints to handle CRUD operations for blog posts.

## Features

- Create new blog posts.
- View all blog posts.
- Edit existing blog posts.
- Delete blog posts.

## Technologies

![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white&style=for-the-badge)
![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white&style=for-the-badge)
![CSS](https://img.shields.io/badge/CSS-1572B6?logo=css3&logoColor=white&style=for-the-badge)
![Body-Parser](https://img.shields.io/badge/Body--Parser-F37626?logo=body-parser&logoColor=white&style=for-the-badge)

## Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/blog-post-app.git
   cd blog-post-app
## Usage

Homepage:
View all blog posts.
- Create a new post:
  Navigate to http://localhost:3000/new and fill out the form to create a new blog post.
- Edit a post:
  Click the "Edit" button on a blog post to modify its content.
- Delete a post:
  Click the "Delete" button on a blog post to remove it.
  
## Routes

- API Routes (index.js)
GET /posts: Retrieve all blog posts.
GET /posts/:id: Retrieve a specific post by ID.
POST /posts: Create a new blog post.
PATCH /posts/:id: Update a specific post by ID.
DELETE /posts/:id: Delete a specific post by ID.

- Front-End Routes (server.js)
GET /: Render the main page with all blog posts.
GET /new: Render the page to create a new post.
GET /edit/:id: Render the page to edit an existing post.
POST /api/posts: Handle form submission to create a new post.
POST /api/posts/:id: Handle form submission to update an existing post.
GET /api/posts/delete/:id: Handle deletion of a post.

## Contact

For any questions or suggestions, please feel free to reach out.
-📧 Email: mahalleom794@gmail.com
  
   
