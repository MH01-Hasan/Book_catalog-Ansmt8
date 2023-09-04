Book catallog server
Live Link:https://book-catallog-server-lbr599tom-mh01-hasan.vercel.app



Table of Contents
Application Routes
User
Category
Books
Orders

Application Routes
User
POST /api/v1/auth/signup: Create a new user.
POST /api/v1/auth/signin: Login user.
GET /api/v1/users: Get a list of all users.
GET /api/v1/users/68d33f5f-26e6-460f-971f-48f902d60a28: Get a single user by ID.
PATCH /api/v1/users/68d33f5f-26e6-460f-971f-48f902d60a28: Update a user by ID.
DELETE /api/v1/users/68d33f5f-26e6-460f-971f-48f902d60a28: Delete a user by ID.
GET /api/v1/profile: Get the user's profile.



Category
POST /api/v1/categories/create-category: Create a new category.
GET /api/v1/categories: Get a list of all categories.
GET /api/v1/categories/0a414922-c0e4-4143-8ca9-5b66d634978b: Get a single category by ID.
PATCH /api/v1/categories/0a414922-c0e4-4143-8ca9-5b66d634978b: Update a category by ID.
DELETE /api/v1/categories/0a414922-c0e4-4143-8ca9-5b66d634978b: Delete a category by ID.




Books
POST /api/v1/books/create-book: Create a new book.
GET /api/v1/books: Get a list of all books.
GET /api/v1/books/0a414922-c0e4-4143-8ca9-5b66d634978b/category: Get all books in a specific category by category ID.
GET /api/v1/books/615f7860-5528-4934-9f76-9ee1c0c74c02: Get a single book by ID.
PATCH /api/v1/books/615f7860-5528-4934-9f76-9ee1c0c74c02: Update a book by ID.
DELETE /api/v1/books/615f7860-5528-4934-9f76-9ee1c0c74c02: Delete a book by ID.


Orders
POST /api/v1/orders/create-order: Create a new order.
GET /api/v1/orders: Get a list of all orders.
GET /api/v1/orders/ed86c3c8-651a-4567-8afd-65251f1c7257: Get a single order by order ID.#   B o o k _ c a t a l o g - A n s m t 8  
 