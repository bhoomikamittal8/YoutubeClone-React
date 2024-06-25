# YouTube Clone Web App 
live preview - https://youtubeclone-bm.netlify.app

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Deployment](#deployment)

## Introduction
This project is a YouTube clone web application built using React JS. The application utilizes the YouTube Data API to fetch a list of YouTube videos and provides real-time statistics for each video. The app is designed to mimic the core functionalities of YouTube, providing users with an intuitive interface to search for and view videos.

## Features
- **Video List Display**: Display a list of YouTube videos based on the search query.
- **Real-time Statistics**: View real-time statistics such as views, likes, and comments for each video.
- **Responsive Design**: The application is responsive and works on various devices and screen sizes.
- **Deployed on Netlify**: The application is deployed and accessible via Netlify.

## Technologies Used
- **React JS**: A JavaScript library for building user interfaces.
- **YouTube Data API**: An API to access YouTube data.
- **Axios**: A promise-based HTTP client for making API requests.
- **HTML**: For the structuring
- **CSS**: Styling the components.
- **Netlify**: A platform for deploying web applications.

## Setup and Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/bhoomikamittal8/YouTubeClone-React.git
   cd YouTubeClone-React
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Set up the YouTube Data API**:
   - Obtain an API key from the [Google Developer Console](https://developers.google.com/youtube/v3/getting-started).
   - Create a `.env` file in the root directory and add your API key:
     ```plaintext
     REACT_APP_YOUTUBE_API_KEY=your_api_key_here
     ```

4. **Start the development server**:
   ```bash
   npm start
   ```

5. **Open the application**:
   - Navigate to `http://localhost:3000` in your web browser.

## Deployment
The application is deployed using Netlify. Follow these steps to deploy your own instance:
1. **Build the application**:
   ```bash
   npm run build
   ```

2. **Deploy to Netlify**:
   - Log in to your Netlify account.
   - Create a new site and link it to your GitHub repository.
   - Configure the build settings:
     - **Build command**: `npm run build`
     - **Publish directory**: `build`
   - Deploy the site.

## Contact 📞

#### If you have any doubt feel free to email me or hit me up on [LinkedIn](https://www.linkedin.com/in/bhoomikamittal/)
