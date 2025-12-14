# Favorite Films

A web application for discovering and managing your favorite movies from different years. Built as part of the Web Technologies course at Insper - Computer Engineering.

[![Live Demo](https://img.shields.io/badge/demo-live-success?style=for-the-badge)](https://tecweb-front-civita-caio-8bgj.vercel.app/)
[![React](https://img.shields.io/badge/React-18.2.0-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://reactjs.org/)
[![Axios](https://img.shields.io/badge/Axios-1.3.6-5A29E4?style=for-the-badge&logo=axios&logoColor=white)](https://axios-http.com/)
[![Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com)
[![Railway](https://img.shields.io/badge/Backend-Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)](https://railway.app)

## Overview

Favorite Films is a responsive web application that allows users to explore movies by year and maintain a personalized list of favorites. The application integrates with the Movies Mini Database API to fetch movie data and provides a clean, interactive interface for managing your movie collection.

**Live Application:** [https://tecweb-front-civita-caio-8bgj.vercel.app/](https://tecweb-front-civita-caio-8bgj.vercel.app/)

## Features

- **Year-Based Movie Search**: Browse movies from 1960 to 2021 by selecting a specific year
- **Favorite Management**: Add movies to your personal favorites list with a simple click
- **CRUD Operations**: Full Create, Read, Update, and Delete functionality for managing favorites
- **Modal Component**: Clean modal interface for viewing and managing your favorite movies
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Interactive Animations**: Smooth hover effects and click animations for enhanced user experience
- **Real-time Updates**: Instant synchronization with backend API

## Technology Stack

### Frontend
- **React** (v18.2.0) - UI framework
- **Axios** (v1.3.6) - HTTP client for API requests
- **React Modal** (v3.16.1) - Modal component for favorites list
- **CSS3** - Styling and animations

### Backend
- **REST API** - Backend hosted on Railway
- **Movies Mini Database API** - External movie data source via RapidAPI

### Deployment
- **Frontend**: Vercel
- **Backend**: Railway

## Project Structure

```
FavoriteFilms/
├── caiotivitafilmes-frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   │   └── Movie/
│   │   │       ├── Movie.js
│   │   │       └── Movie.css
│   │   ├── App.js
│   │   ├── App.css
│   │   └── index.js
│   └── package.json
├── package.json
└── README.md
```

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/pedrocivita/FavoriteFilms.git
cd FavoriteFilms
```

2. Install root dependencies:
```bash
npm install
```

3. Navigate to the frontend directory and install dependencies:
```bash
cd caiotivitafilmes-frontend
npm install
```

4. Start the development server:
```bash
npm start
```

The application will open at [http://localhost:3000](http://localhost:3000)

### Building for Production

```bash
npm run build
```

This creates an optimized production build in the `build` folder.

## Usage

1. **Search for Movies**: Enter a year between 1960 and 2021 in the search box and click "GO"
2. **Add to Favorites**: Click the heart button on any movie card to add it to your favorites
3. **View Favorites**: Click the star button in the top corner to open the favorites modal
4. **Remove from Favorites**: Click the "Delete" button next to any movie in your favorites list

## API Integration

The application integrates with two APIs:

- **Movies Mini Database API** (RapidAPI): Fetches movie data by year
- **Custom Backend API** (Railway): Manages user's favorite movies with full CRUD operations

## Development

### Available Scripts

- `npm start` - Runs the app in development mode
- `npm test` - Launches the test runner
- `npm run build` - Builds the app for production
- `npm run eject` - Ejects from Create React App (one-way operation)

## Academic Context

This project was developed as Project 2 for the Web Technologies (TecWeb) course at Insper - Computer Engineering program. The project demonstrates advanced frontend development skills including:

- Component-based architecture
- State management with React hooks
- API integration and asynchronous data handling
- Responsive design principles
- User experience optimization

**Developed by**: Pedro Civita and Caio Boa

## Contact

**Pedro Civita**

- Email: pedrocivita@gmail.com
- LinkedIn: [linkedin.com/in/pedro-civita](https://www.linkedin.com/in/pedro-civita/)
- GitHub: [@pedrocivita](https://github.com/pedrocivita)

## License

This project is part of an academic portfolio and is available for educational purposes.

## Acknowledgments

- Insper - Instituto de Ensino e Pesquisa
- Web Technologies Course instructors
- Movies Mini Database API (RapidAPI)
- Project partner: Caio Boa
