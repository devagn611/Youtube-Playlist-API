

# YouTube Playlist Fetcher

## Overview

The **YouTube Playlist Fetcher** is a web application that allows users to retrieve and display videos from a specified YouTube playlist. This application provides a user-friendly interface to explore videos along with essential details such as titles, thumbnails, and publication dates.

## Features

- Fetch videos from any public YouTube playlist using the playlist ID.
- Customize the number of results displayed from the playlist.
- Clean and responsive user interface that resembles YouTube's design.
- Easy navigation and seamless experience for users.

## API Endpoint

The API is hosted on Vercel and can be accessed at:

- **API Endpoint**: [Click Here](https://youtube-playlist-api.vercel.app)

## Main Web Application

You can access the main web application at:

- **Web Application**: [Click Here](https://youtube-playlist-fetcher.vercel.app)

## How It Works

1. **Enter Playlist ID**: Users input the YouTube playlist ID they wish to fetch videos from.
2. **Specify Max Results**: Optionally, users can specify the maximum number of results to display.
3. **Fetch Videos**: The application fetches videos using the YouTube Data API.
4. **Display Videos**: The videos are displayed in a grid format, showing thumbnails, titles, and links to watch each video.

## Installation

To set up the project locally, follow these steps:

### Prerequisites

- Node.js (>= 14.x)
- npm or yarn

### Clone the Repository

```bash
git clone https://github.com/devagn611/youtube-playlist-fetcher.git
cd youtube-playlist-fetcher
```

### Install Dependencies

```bash
npm install
# or
yarn install
```

### Environment Variables

Create a `.env` file in the root directory and add your YouTube API key:

```env
YOUTUBE_API_KEY=your_youtube_api_key_here
```

### Start the Application

```bash
npm start
# or
yarn start
```

Visit `http://localhost:3000` in your browser to view the application.

## Deployment

The application is deployed on Vercel. Any changes made to the main branch will automatically trigger a new deployment.


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


