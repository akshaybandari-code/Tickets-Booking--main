# Tickets Booking

A React + Vite web application for browsing movies, selecting seats, and booking tickets.

## Features

- Movie listing and details pages
- Search movies by title
- Protected routes for login-only access
- Seat selection for booking confirmation
- Booking history and profile pages
- Local JSON data server support

## Project structure

- `src/` - React app source files
- `src/components/` - reusable UI components
- `src/pages/` - page views for app routes
- `public/` - static assets
- `data/db.json` - mock data for local JSON server

## Technologies used

- React 19
- Vite
- React Router DOM
- json-server
- React Spinners
- UUID for unique identifiers
- ESLint

## Installation

1. Clone the repository:

```bash
git clone https://github.com/edharanagasaimanohar-lgtm/Tickets-Booking-.git
cd Tickets-Booking-
```

2. Install dependencies:

```bash
npm install
```

## Running the app

Start the development server:

```bash
npm run dev
```

Then open the local URL shown in the terminal.

## Mock API server

If you want to run the local JSON data server:

```bash
npx json-server --watch data/db.json --port 3000
```

## Available scripts

- `npm run dev` - run the app in development mode
- `npm run build` - build the production app
- `npm run preview` - preview the production build locally
- `npm run lint` - run ESLint for source code

## Deployment

This project can be deployed to services like Vercel, Netlify, or GitHub Pages.

## License

This repository is open source and available under the MIT License.
