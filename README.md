# Cautious Doodle

A basic React project built with Vite.

## Prerequisites

- Node.js 18+ (developed and tested with Node 20)
- npm (comes with Node.js)

## Getting Started

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Start the development server:**
   ```bash
   npm run dev
   ```
   Open [http://localhost:5173](http://localhost:5173) in your browser to view the app.

3. **Build for production:**
   ```bash
   npm run build
   ```
   The built files will be in the `dist` directory.

4. **Preview the production build:**
   ```bash
   npm run preview
   ```

## Project Structure

```
cautious-doodle/
├── public/                 # Static assets
├── src/
│   ├── App.jsx            # Main App component
│   ├── App.css            # App-specific styles
│   ├── main.jsx           # Entry point
│   └── index.css          # Global styles
├── index.html             # HTML template
├── vite.config.js         # Vite configuration
└── package.json           # Project dependencies and scripts
```

## Features

- ⚡️ Fast development with Vite
- ⚛️ React 19 
- 🎨 Modern CSS with dark/light mode support
- 🔥 Hot Module Replacement (HMR)
- 📦 Optimized production builds

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally