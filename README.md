# Spotify Clone

A Spotify-inspired music player built with React and Vite. Features a fully functional audio player with play/pause, next/previous track, and a real-time seek bar. Album and song browsing with dynamic routing using React Router DOM. Global player state managed with React Context API, providing audio controls and playback time across all components. Styled with Tailwind CSS.

![Spotify Clone](https://github.com/user-attachments/assets/7e68ff7b-e72e-4776-a3b1-845f7c913be5)
🔗 [Live Demo](https://spotify-clone-omega-neon-91.vercel.app/)

## Features

- Browse albums and songs on the home page
- Click any album to navigate to its dedicated page with dynamic background color matching the album art
- Fully functional audio player — play, pause, next, previous track
- Real-time seek bar that updates as the song plays — click anywhere to seek
- Song progress and total duration displayed in proper time format
- Global player state shared across all components using React Context API
- Dynamic routing with React Router DOM — each album has its own URL
- Responsive design with Tailwind CSS — sidebar hidden on mobile

## Tech Stack

- **React** — component-based UI library
- **Vite** — build tool and dev server
- **Tailwind CSS** — utility-first styling
- **React Router DOM** — dynamic routing and navigation
- **React Context API** — global state management for audio player
- **HTML Audio API** — native browser audio playback and controls

## Getting Started

### Prerequisites
- Node.js installed on your machine

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/edwinalexandervargas/spotify-clone.git
   cd spotify-clone
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Start the development server
   ```bash
   npm run dev
   ```

## What I Learned

- Managing global audio player state across multiple components with React Context API
- Implementing the HTML Audio API for playback controls including play, pause, next, previous, and seeking
- Building a real-time seek bar that reflects current playback position
- Dynamic routing with React Router DOM using URL parameters to load album-specific data
- Extracting URL parameters with `useParams` to render dynamic content
- Changing background colors dynamically based on album data
- Using `useLocation` to detect the current route and conditionally apply styles
- Utility-first styling with Tailwind CSS for a dark themed UI
