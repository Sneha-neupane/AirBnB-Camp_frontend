# AirBnB Camp – Frontend

A responsive frontend application inspired by Airbnb, built to display camp listings with modern UI, interactive components, dynamic routing, and integration with the backend API. This project is part of a full-stack MERN application where users can explore camps, view details, and interact with the platform.

## Features

- Fully responsive UI with clean layout

- Camp listing page with cards and dynamic camp details

- Integration with backend API for fetching camp data

- User authentication support (login and register pages)

- Protected routes for authenticated users

- Reusable UI components

- State management using React hooks

- Routing with React Router

- Environment variable support

## Tech Stack

- React

- Vite

- React Router

- Axios

- Tailwind CSS 

- Context API / local storage for auth handling

## Folder Structure (Typical)
AirBnBCamp_frontend/
│── public/
│── src/
│   │── components/
│   │── pages/
│   │── context/
│   │── hooks/
│   │── utils/
│   │── App.jsx
│   │── main.jsx
│── .env
│── package.json
│── vite.config.js
│── README.md
## Getting Started
1. Clone the Repository
git clone https://github.com/Sneha-neupane/AirBnB-Camp_frontend.git
2. Navigate to the Project Directory
cd AirBnB-Camp_frontend
3. Install Dependencies
npm install
4. Setup Environment Variables

## Create a .env file in the root directory:

VITE_API_URL=<your-backend-api-url>

Example:

VITE_API_URL=http://localhost:5000/api
5. Start Development Server
npm run dev

Your app should now be running at:

http://localhost:5173
Build for Production
npm run build

The optimized output will be in the dist folder.

## Backend Repository 
https://github.com/Sneha-neupane/AirBnB-Camp_backend.git

## Deployment

You can deploy this frontend using platforms like:

- Netlify

- Vercel

- Render

- GitHub Pages

Make sure your .env is configured properly in deployment settings.

## Contribution

Contributions are welcome. To contribute:

Fork the repository

Create a new feature branch

Commit your changes

Submit a pull request

## License

This project is released under the MIT License.
