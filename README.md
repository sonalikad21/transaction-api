# transaction-api
A RESTful API built with Node.js, Express, and MongoDB to manage product transactions. Features include search, pagination, and monthly sales statistics. The API initializes the database using data from a third-party source and supports efficient transaction management.
Here’s a description you can use for your GitHub project:

---

**Project Name**: **Transaction API Using Node.js and MongoDB**

**Description**:  
A RESTful API built using Node.js, Express, and MongoDB to manage product transactions. The API supports searching, pagination, and provides monthly sales statistics. It initializes by fetching data from a third-party JSON source and stores the transactions in a MongoDB database.

**Features**:
- **CRUD operations** for managing product transactions.
- **Search** by title, description, and price.
- **Pagination** for listing transactions.
- **Monthly statistics** on total sales, sold, and unsold items.
- **Database initialization** from a third-party API.

**Technologies Used**:
- **Node.js** and **Express** for the server-side logic.
- **MongoDB** and **Mongoose** for database and data modeling.
- **Axios** for HTTP requests to fetch initial data.
  
**Setup**:
1. Clone the repository and navigate to the project directory.
2. Run `npm install` to install dependencies.
3. Ensure MongoDB is running locally or in the cloud.
4. Start the server with `node app.js` or `nodemon app.js`.

**API Endpoints**:
- `GET /initialize`: Initializes the database with third-party data.
- `GET /transactions`: Retrieves paginated transactions with search filters.
- `GET /statistics?month=<month>`: Fetches sales statistics for a specific month.

---
