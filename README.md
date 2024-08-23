# Vue Game Leaderboard

## Project Overview
This project is a Vue.js frontend application designed to work with the [restful-game-api](https://github.com/Abhishek-Balram/restful-game-api). It provides a user-friendly interface for viewing and interacting with game data, including player information and scores. This project showcases frontend development skills, particularly with Vue.js, and demonstrates the ability to integrate with a RESTful API.

## Key Features
- Vue.js based frontend for game data visualization
- Integration with restful-game-api
- Player leaderboard display
- Individual player score views


## Technology Stack
- **Frontend Framework**: Vue.js 3
- **API Communication**: Axios
- **Build Tool**: Vite

## Project Structure
```
vue-game-leaderboard/
│
├── src/
│   ├── components/
│   │   ├── LeaderBoard.vue
│   │   ├── PlayerDetails.vue
│   │   └── ScoreCard.vue
│   ├── views/
│   │   ├── Home.vue
│   │   └── PlayerView.vue
│   ├── services/
│   │   └── api.js
│   ├── store/
│   │   └── index.js
│   ├── router/
│   │   └── index.js
│   ├── App.vue
│   └── main.js
│
├── public/
│   └── index.html
│
├── package.json
├── vite.config.js
└── README.md
```

## Setup and Installation
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/vue-game-leaderboard.git
   cd vue-game-leaderboard
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Create a `.env` file in the root directory and add the API base URL:
   ```
   VITE_API_BASE_URL=http://localhost:5001
   ```

4. Run the development server:
   ```
   npm run dev
   ```

5. Access the application at `http://localhost:3000` (or the port specified by Vite)

## API Integration
This frontend application is designed to work with the [restful-game-api](https://github.com/Abhishek-Balram/restful-game-api). Ensure that the API is running and accessible before using this frontend. Update the `VITE_API_BASE_URL` in the `.env` file to point to your API's location.

## Features to Implement
- [ ] Display all players and their scores in a leaderboard
- [ ] View individual player details and scores
- [ ] Update player scores through the UI
- [ ] Add new players

## Future Enhancements
- Implement more advanced data visualizations (e.g., charts, graphs)
- Add user authentication and personalized dashboards
- Integrate with a real game to display live data
- Implement progressive web app features for offline functionality
- Add internationalization support for multiple languages
- Implement real-time updates using WebSockets (optional)
- Add authentication for admin functions (optional)


## Contact
Abhishek Balram - abhishek.balram@icloud.com


## Acknowledgments
- [Vue.js Documentation](https://vuejs.org/)
- [Restful Game API](https://github.com/Abhishek-Balram/restful-game-api)
