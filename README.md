<div align="center">
  
  # E-Commerce API Back End
  > Module 13 Challenge

![JavaScript Badge](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
[![Node.js Badge](https://img.shields.io/badge/Node.js-393%3F?style=for-the-badge&logo=node.js&logoColor=green)](https://nodejs.org/en/)
[![Express Badge](https://img.shields.io/badge/Express-4.x-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)
[![Sequelize Badge](https://img.shields.io/badge/Sequelize-6.x-52B0E7?style=for-the-badge&logo=sequelize&logoColor=white)](https://sequelize.org/)
[![PostgreSQL Badge](https://img.shields.io/badge/PostgreSQL-13-316192?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![dotenv Badge](https://img.shields.io/badge/dotenv-8.2.0-ECD53F?style=for-the-badge&logo=dotenv&logoColor=white)](https://www.npmjs.com/package/dotenv)

</div>

## Description

This repository contains the code for the **E-Commerce API Back End** application. This back end serves as a RESTful API for managing an e-commerce platform. The application is built using Node.js, Express, Sequelize, and PostgreSQL. It provides a robust framework for handling product catalogs, categories, and tags, allowing for comprehensive management of an e-commerce store's inventory and related data.

### Key Features:

- **Product Management:** Create, read, update, and delete products in the database.
- **Category Management:** Manage product categories with full CRUD operations.
- **Tag Management:** Assign tags to products, allowing for flexible categorization.
- **Seamless Associations:** Products are associated with categories and tags, enabling complex queries and filtering.
- **Many-to-Many Relationships:** Products can belong to multiple tags, and tags can be associated with multiple products through the `ProductTag` model.

## Instruction Video

[E-commerce backend.webm](https://github.com/user-attachments/assets/45838bf2-8e97-4392-9a4e-2852664f72da)

## Installation

To run this application, follow these steps:

1. **Ensure Node.js is Installed:**

   You will need Node.js installed on your computer. Check if you have Node.js by typing `node -v` in your command line. You should see a version number. If Node.js is not installed, visit the [Node.js website](https://nodejs.org/en) to install it.

2. **Clone the Repository:**

   Clone this project repository to your computer:

   ```bash
   git clone https://github.com/leontran44/e-commerce-backend.git
   cd e-commerce-backend
   ```

3. **Install Dependencies:**

   Use the following command to install the required dependencies:

   ```bash
   npm install
   ```

4. **Set Up the Database:**

   Create a PostgreSQL database named `ecommerce_db`. Run the provided SQL schema located in the `db/schema.sql` file to create the necessary tables. Optionally, seed the database using the `npm run seed` command to populate the database with initial data.

5. **Set Up Environment Variables:**

   Create a `.env` file in the root directory of the project. Add the following environment variables to the file:

   ```plaintext
   DB_HOST=localhost
   DB_NAME=ecommerce_db
   DB_USER=postgres
   DB_PASSWORD=your_password
   ```

   Replace `your_password` with your PostgreSQL password.

6. **Start the Server:**

   Start the Express server using the following command:

   ```bash
   npm start
   ```

   The server will start running on `http://localhost:3001`.

## Usage

- Node.js: JavaScript runtime environment.
- Express.js: Web framework for Node.js.
- Sequelize: Promise-based Node.js ORM for PostgreSQL.
- PostgreSQL: Relational database management system.
- dotenv: Environment variable management.
- Insomnia Core: API testing tool.

## API Routes

### The API provides the following routes for managing products, categories, and tags:

- **GET** `/api/products` - Retrieve all products.
- **GET** `/api/products/:id` - Retrieve a single product by its ID.
- **POST** `/api/products` - Create a new product.
- **PUT** `/api/products/:id` - Update an existing product.
- **DELETE** `/api/products/:id` - Delete a product by its ID.
- **GET** `/api/categories` - Retrieve all categories.
- **GET** `/api/categories/:id` - Retrieve a single category by its ID.
- **POST** `/api/categories` - Create a new category.
- **PUT** `/api/categories/:id` - Update an existing category.
- **DELETE** `/api/categories/:id` - Delete a category by its ID.
- **GET** `/api/tags` - Retrieve all tags.
- **GET** `/api/tags/:id` - Retrieve a single tag by its ID.
- **POST** `/api/tags` - Create a new tag.
- **PUT** `/api/tags/:id` - Update an existing tag.
- **DELETE** `/api/tags/:id`- Delete a tag by its ID.

## License

[MIT License](https://opensource.org/licenses/MIT)

## Contact

- GitHub: [leontran44](https://github.com/leontran44)
- Email: [Leon Tran](mailto:leontran44@gmail.com)
- LinkedIn: [Leon Tran](https://www.linkedin.com/in/hoangqtran/)
