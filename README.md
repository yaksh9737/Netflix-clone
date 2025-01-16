<h1 align="center">MERN Netflix Clone 🎬</h1>

Netflix Clone is a MERN stack application inspired by Netflix, offering
functionalities such as user authentication, movie browsing, and
watchlist management.

## Installation

Clone the repository and install dependencies for both backend and
frontend.

``` bash
git clone https://github.com/yaksh9737/Netflix-clone.git
cd Netflix-clone
```

### Backend Setup

Navigate to the `backend` folder and install dependencies:

``` bash
cd backend
npm install
```

Create a `.env` file in the backend directory with the following
content:

``` bash
PORT=5000
MONGO_URI=your_mongo_uri
NODE_ENV=development
JWT_SECRET=your_jwt_secret
TMDB_API_KEY=your_tmdb_api_key
```

Replace placeholders with your configurations: - `MONGO_URI`: MongoDB
connection string - `JWT_SECRET`: JSON Web Token secret -
`TMDB_API_KEY`: API key from [TMDB](https://www.themoviedb.org/)

Build and start the backend server:

``` bash
npm run build
npm start
```

### Frontend Setup

Navigate to the `frontend` folder and install dependencies:

``` bash
cd ../frontend
npm install
```

Create a `.env` file in the frontend directory with the following
content:

``` bash
NEXT_PUBLIC_API_URL=http://localhost:5000
```

Start the frontend server:

``` bash
npm run build
npm start
```

The application should now be accessible at `http://localhost:3000`.

## Usage

1.  **Register and Log In**:
    -   Create an account via the sign-up page.
    -   Log in using the registered credentials.
2.  **Browse Movies and Shows**:
    -   View popular, top-rated, and upcoming movies and TV shows.
    -   Use the search functionality to find specific content.
3.  **Manage Your Watchlist**:
    -   Add movies or shows to your watchlist by clicking "Add to
        Watchlist."
    -   Access your watchlist from the user profile.
4.  **Watch Trailers**:
    -   View details and trailers for selected movies or shows.

## Contributing

Pull requests are welcome! For significant changes, please open an issue
to discuss your ideas first. Ensure that tests are updated as necessary.

## License

[MIT](https://choosealicense.com/licenses/mit/)

------------------------------------------------------------------------

Happy Streaming! 🎥


