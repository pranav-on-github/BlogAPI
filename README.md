# BlogAPI
Python Django CRUD API with MySQL and Django Rest Framework

## Features

- Create, retrieve, update, and delete blog posts.
- Add comments to blog posts and retrieve comments for a specific blog post.
- Like and dislike functionality for blog posts.
- User authentication to protect sensitive operations.
- File Upload support for adding images to blog posts.

- ## API Endpoints

- `GET /api/blog/`: Get all blog posts.
- `POST /api/addblog/`: Create a new blog post.
- `GET /api/blog/<slug:slug>/`: Get details of a specific blog post.
- `PUT /api/blog/<slug:slug>/`: Update a specific blog post.
- `DELETE /api/blog/<slug:slug>/`: Delete a specific blog post.
- `POST /api/blog/<int:id>/like/`: Like or dislike a blog post.
- `POST /api/blogs/<slug:slug>/comments/`: Add a comment to a blog post.
- `GET /api/blogs/<slug:slug>/comment/`: Get comments for a specific blog post.
- `POST /api/savefile/`: Upload a file (image) for a blog post.
- `GET /api/getuser/`: Get details of the authenticated user.
