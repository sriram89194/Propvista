# Propvista Frontend

React-based frontend application for the Propvista real estate management platform.

## Prerequisites

- Node.js (v14 or higher)
- npm or yarn

## Installation

```bash
npm install
```

## Available Scripts

### `npm start`
Runs the app in development mode at [http://localhost:3000](http://localhost:3000)

### `npm build`
Builds the app for production to the `build` folder

### `npm test`
Launches the test runner in interactive watch mode

## Project Structure

```
src/
├── components/      # Reusable React components
├── pages/          # Page components
├── services/       # API services
├── hooks/          # Custom React hooks
├── utils/          # Utility functions
├── styles/         # Global styles
├── App.js          # Main App component
└── index.js        # Entry point
```

## Environment Variables

Copy `.env.example` to `.env.local` and update the values:

```
REACT_APP_API_URL=http://localhost:5000
```

## Features

- Property listing and management
- Search and filtering
- User authentication
- Responsive design

## Contributing

Please read the main README.md for contribution guidelines.

## License

MIT License
