The application will have the following components designed to communicate with each other to ensure a smooth user experience:

The user interface for the Checkers app will be the user's browser

1. On the front-end, JavaScript will handle the user interface which will have the following responisibilities:

    - renders the game board
    - manages user interactions
    - communicates with the back-end server

2. On the back-end, a Python server will manage the following:

    - implements game logic
    - manages user management
    - communicates with the database

3. MYSQL database will be responsible for the following:

    - stores the game data
    - user profiles
    - other relevant information we might not know about yet

The flow of the game should be as follows:

    -The user interacts with the UI (JS Front-end) in their browser
    -The Front-end communicates with the Back-end server using Restful API calls over HTTP or HTTPS which will send request for game moves, user authentication and other actions
    -The Back-end server processes the requests, executes the game logic, performs database queries or updates as needed, and sends responses back to the Front-end
    -The Back-end server interacts with the MYSQL database to store and retrieve game data, user profiles, and other relevant information.