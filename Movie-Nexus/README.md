Fasal Assignment
# Movie Nexus

Movie Nexus is a web application that allows users to search for movies, view their details, and create personalized playlists. This project was developed as part of the FASAL assignment.

## Features

- User authentication (Sign In / Sign Up)
- Search for movies and view details (using the OMDB API)
- Create private and public movie lists (similar to playlists)
- View and manage your created movie lists
- Responsive and user-friendly interface

## Technologies Used

- **Front-end**: HTML, CSS, EJS (Embedded JavaScript templating)
- **Back-end**: Node.js, Express.js
- **Database**: MongoDB (with Mongoose ODM)
- **Authentication**: Passport.js
- **Other Libraries**: express-ejs-layouts, cookie-parser, express-session, connect-mongo, dotenv

## Installation

1. Clone the repository:

```

```

2. Navigate to the project directory:

```
cd movie-nexus
```

3. Install the dependencies:

```
npm install
```

4. Create a `.env` file in the project root and add the following environment variables:

```
MONGODB_URL=your_mongodb_connection_string
```

5. Start the development server:

```
npm start
```

6. Open your browser and visit `http://localhost:8000` to access the application.

## Usage

1. Sign up for a new account or log in if you already have one.
2. Use the search bar to find movies and view their details.
3. Click the "Add to List" button to add a movie to a new or existing list.
4. Manage your lists by navigating to the "My Lists" page.
5. Toggle the privacy setting of your lists to make them public or private.

## Contributing

Contributions are welcome! If you find any issues or want to add new features, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- [OMDB API](http://www.omdbapi.com/) for providing movie data
- [Passport.js](http://www.passportjs.org/) for authentication middleware
- [Mongoose](https://mongoosejs.com/) for MongoDB object modeling