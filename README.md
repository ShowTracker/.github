# Movie and Series Tracker

## Description

The Movie and Series Tracker is a web-based application that allows users to keep track of their watched movies and series. The application provides features to add, view, and manage the user's watchlist. Users can mark movies and series as watched, rate them, and leave reviews. The application also offers a search functionality to discover new movies and series.

## Features

- User registration and authentication
- Add movies and series to the watchlist
- Mark movies and series as watched
- Rate movies and series
- Leave reviews for movies and series
- Search functionality to find movies and series
- User profile with watchlist history
- Recommendations based on user preferences

## Technologies Used

- Frontend:
  - HTML, CSS, JavaScript
  - React.js (or Angular, Vue.js)
  - Bootstrap (or Material UI, Tailwind CSS)

- Backend:
  - Node.js
  - Express.js (or Flask, Django)
  - PostgreSQL (or MySQL, MongoDB)

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo.git
   ```

2. Install dependencies:

   ```bash
   cd your-repo
   npm install
   ```

3. Configure the database:

   - Create a PostgreSQL database.
   - Update the database configuration file (`config.js` or similar) with your database credentials.

4. Run the application:

   ```bash
   npm start
   ```

5. Access the application:

   Open your web browser and visit `http://localhost:3000` to access the Movie and Series Tracker application.

## API Endpoints

The following API endpoints are available:

- `GET /movies` - Retrieve all movies in the watchlist.
- `GET /movies/{id}` - Retrieve a specific movie by its ID.
- `POST /movies` - Add a new movie to the watchlist.
- `PUT /movies/{id}` - Update an existing movie.
- `DELETE /movies/{id}` - Delete a movie from the watchlist.
- `GET /series` - Retrieve all series in the watchlist.
- `GET /series/{id}` - Retrieve a specific series by its ID.
- `POST /series` - Add a new series to the watchlist.
- `PUT /series/{id}` - Update an existing series.
- `DELETE /series/{id}` - Delete a series from the watchlist.

## Database Schema

The application uses the following database schema:

### Movies Table

| Column       | Type         |
| ------------ | ------------ |
| id           | INT (PK)     |
| title        | VARCHAR      |
| release_date | DATE         |
| genre        | VARCHAR      |
| rating       | FLOAT        |
| review       | VARCHAR      |
| watched      | BOOLEAN      |

### Series Table

| Column       | Type         |
| ------------ | ------------ |
| id           | INT (PK)     |
| title        | VARCHAR      |
| release_date | DATE         |
| genre        | VARCHAR      |
| rating       | FLOAT        |
| review       | VARCHAR      |
| watched      | BOOLEAN      |

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Contact

For any questions or inquiries, please contact [torres.yanna03@gmail.com].

Feel free to modify and expand this README file to suit your specific project requirements.
