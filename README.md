# Fire-code

FireCode is better version of coding platform for developers to practice coding problems and improve their skills. This project was created as a full-stack project _(my first full-stack project)_ using Express, MongoDB, Mongoose, TypeScript,TypeScript React (TSX), CSS3, and Tailwind CSS.

# Installation


```bash
cd FireCode/server
npm install
cd ../client
npm install
```

### Start the client in the `client` directory:

```bash
npm start
```

### Configure the MongoDB Database and JWT Secret:


-   `MONGODB_URI`: Set this variable to your MongoDB connection string.
-   `ACCESS_TOKEN_SECRET`: Set this variable to a secret key for JWT access tokens.

### Configure the API URL:

To use your own API, open the `client/src/App.tsx` file and find the `API_URL` constant. Update its value to match the URL of your deployed server (`http://localhost:80`).



# Features

-   User authentication: Users can create an account, log in, and log out, delete account.
-   Coding problems: Users can browse coding problems, submit solutions.
-   User profile: Users can view their profile, including their solved problems and submissions.

# Technologies Used

-   Express: A web framework for Node.js
-   MongoDB: A NoSQL database
-   Mongoose: A MongoDB object modeling tool
-   TypeScript: A typed superset of JavaScript
-   TypeScript React: A JavaScript library for building user interfaces with TypeScript
-   Tailwind CSS: A utility-first CSS framework
-   CSS: A stylesheet language used to describe the presentation of a document written in HTML or XML

# Contributing

Contributions are welcome! If you find a bug or have a feature request, please create an issue on GitHub. If you would like to contribute code, please fork the repository and create a pull request.


# Acknowledgments

This project was inspired by LeetCode.
Thanks to the creators of Express, MongoDB, Mongoose, TypeScript, and React.
