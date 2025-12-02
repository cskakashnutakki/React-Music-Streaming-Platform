# React Music Streaming Platform

A modern music streaming application built with React, inspired by Spotify. This project features a sleek UI for browsing albums, playing songs, and managing playlists.

## Features

- **Browse Albums**: View and explore different music albums
- **Music Player**: Play, pause, skip, and control volume
- **Responsive Design**: Optimized for desktop and mobile devices
- **Search Functionality**: Find your favorite songs and artists
- **Playlist Management**: Create and manage custom playlists
- **Audio Controls**: Shuffle, repeat, and queue management

## Tech Stack

- **Frontend**: React 19
- **Build Tool**: Vite
- **Styling**: Tailwind CSS
- **Routing**: React Router DOM
- **Icons & Assets**: Custom SVG icons and audio files

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/cskakashnutakki/React-Music-Streaming-Platform.git
   cd React-Music-Streaming-Platform
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5173` (or the port shown in the terminal).

## Usage

- Browse through the home page to see featured albums
- Click on an album to view its songs
- Use the player controls at the bottom to play music
- Navigate using the sidebar for different sections

## Build for Production

To build the app for production:

```bash
npm run build
```

The built files will be in the `dist` folder.

## Preview Production Build

After building, you can preview the production build:

```bash
npm run preview
```

## Project Structure

```
src/
├── assets/          # Audio files, images, and icons
├── components/      # React components
│   ├── Display.jsx
│   ├── Player.jsx
│   ├── Sidebar.jsx
│   └── ...
├── context/         # React context for state management
└── main.jsx         # App entry point
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is for educational purposes. Please check individual asset licenses for usage rights.
