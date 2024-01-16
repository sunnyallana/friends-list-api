# Friends List API

The Friends List API is a simple RESTful web service built using Node.js and Express.js that allows users to manage a list of friends. Users can register, log in, add, modify, delete, and retrieve details of friends. The API utilizes JSON Web Tokens (JWT) for user authentication and supports basic CRUD operations for friend management.

**Author: Sunny Allana**  
**GitHub: [Sunny Allana](https://github.com/sunnyallana/)**  <br>
**LinkedIn: [Sunny Allana](https://www.linkedin.com/in/sunnyallana/)** <br>
**Instagram: [Sunny Allana](https://www.instagram.com/imsunnyallana/)** <br>


## Features

- User registration and login
- Adding/modifying friend details for registered users
- Retrieving details of friends
- Deleting friends based on email ID

## Technologies Used

- Node.js
- Express.js
- JWT for authentication
- JSON for data storage

## Getting Started

To run the project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/friends-list-api.git
   cd friends-list-api
   ```


2. Install dependencies:

    ```bash
    npm install
    ```

3. Start the application:

    ```bash
    node index.js
    ```

The application will be available at http://localhost:5000.

## API Endpoints
1. Retrieve all friends:

    ```bash
    GET /friends
    ```

Retrieve the details of all friends.

2. Retrieve friend by email:

    ```bash
    GET /friends/:email
    ```

Retrieve details of a specific friend based on the email ID.

3. Add a new friend:

    ```bash
    POST /friends
    ```

Add a new friend by providing email, firstName, lastName, and DOB.

4. Update friend details:

    ```bash
    PUT /friends/:email
    ```

Update the details of a friend with the specified email ID by providing firstName, lastName, and DOB.

5. Delete a friend:

    ```bash
    DELETE /friends/:email
    ```

Delete a friend based on the email ID.

## Usage
1. Register a User:

    ```bash
    POST /register
    ```

Register a new user by providing an email and password.

2. Login:

    ```bash
    POST /login
    ```

Authenticate a user and obtain a JWT token for subsequent requests.

3. Add a Friend:

    ```bash
    POST /friends
    ```

Add a new friend by providing email, firstName, lastName, and DOB.

4. Update Friend Details:
    ```bash
    PUT /friends/:email
    ```

Update the details of a friend with the specified email ID by providing firstName, lastName, and DOB.

5. Delete a Friend:
    ```bash
    DELETE /friends/:email
    ```

Delete a friend based on the email ID.

## License
This project is licensed under the MIT License.

## Acknowledgments
Special thanks to the Node.js and Express.js communities for providing powerful tools for building web applications.