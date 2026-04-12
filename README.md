# CodeCampus

CodeCampus is a React-based learning website with course browsing, authentication pages, a dashboard, wishlist support, and contact/home pages.

## Features

- Home page with navigation and landing content
- Courses listing with wishlist support
- Login and signup pages
- User dashboard for saved content
- Contact page for inquiries

## Tech Stack

- React
- React Router
- Bootstrap / React-Bootstrap
- React Icons
- React Toastify

## Getting Started

### Prerequisites

- Node.js
- npm

### Install dependencies

```bash
npm install
```

### Run the app

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Build for production

```bash
npm run build
```

## Available Scripts

- `npm start` - starts the development server
- `npm test` - starts the test runner
- `npm run build` - creates a production build
- `npm run eject` - ejects Create React App configuration

## Project Structure

- `src/App.js` - main routing and app state
- `src/components/` - shared UI components such as the navbar and course card
- `src/pages/` - page-level views including home, courses, contact, login, signup, and dashboard

## Notes

- The app uses local storage to persist the signed-in user and wishlist data.
- If you are using a newer Node.js version, the `start` script is already configured with `cross-env` for compatibility with the current React scripts setup.
