# Book Catalog Server

Welcome to the Book Catalog Server documentation. This readme provides an overview of the Book Catalog Server's API routes and their functionalities.

## Live Link
Visit the live version of the Book Catalog Server [here](https://book-catallog-server-six.vercel.app).


## Table of Contents
- [Application Routes](#application-routes)
  - [User](#user)
  - [Category](#category)
  - [Books](#books)
  - [Orders](#orders)

## Application Routes

### User
- **POST /api/v1/auth/signup**: Create a new user.
- **POST /api/v1/auth/signin**: Login user.
- **GET /api/v1/users**: Get a list of all users.
- **GET /api/v1/users/4203e0d5-5279-49b2-93f3-6ef74d838b88**: Get a single user by ID.
- **PATCH /api/v1/users/4203e0d5-5279-49b2-93f3-6ef74d838b88**: Update a user by ID.
- **DELETE /api/v1/users/4203e0d5-5279-49b2-93f3-6ef74d838b88**: Delete a user by ID.
- **GET /api/v1/profile**: Get the user's profile.

### Category
- **POST /api/v1/categories/create-category**: Create a new category.
- **GET /api/v1/categories**: Get a list of all categories.
- **GET /api/v1/categories/7e83c8ce-0598-48c2-a9c1-cbeb8f612f22**: Get a single category by ID.
- **PATCH /api/v1/categories/7e83c8ce-0598-48c2-a9c1-cbeb8f612f22**: Update a category by ID.
- **DELETE /api/v1/categories/7e83c8ce-0598-48c2-a9c1-cbeb8f612f22**: Delete a category by ID.

### Books
- **POST /api/v1/books/create-book**: Create a new book.
- **GET /api/v1/books**: Get a list of all books.
- **GET /api/v1/books/9e67f495-9857-4a01-a7a1-c610876b0d8b/category**: Get all books in a specific category by category ID.
- **GET /api/v1/books/9e67f495-9857-4a01-a7a1-c610876b0d8b**: Get a single book by ID.
- **PATCH /api/v1/books/9e67f495-9857-4a01-a7a1-c610876b0d8b**: Update a book by ID.
- **DELETE /api/v1/books/9e67f495-9857-4a01-a7a1-c610876b0d8b**: Delete a book by ID.

### Orders
- **POST /api/v1/orders/create-order**: Create a new order.
- **GET /api/v1/orders**: Get a list of all orders.
- **GET /api/v1/orders/ed86c3c8-651a-4567-8afd-65251f1c7257**: Get a single order by order ID.


#
