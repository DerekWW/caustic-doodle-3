# Cautious Doodle

A basic React project built with Vite.

## Prerequisites

- Bun 1.0+ (developed and tested with Bun 1.2.22)

## Getting Started

1. **Install dependencies:**
   ```bash
   bun install
   ```

2. **Start the development server:**
   ```bash
   bun run dev
   ```
   Open [http://localhost:5173](http://localhost:5173) in your browser to view the app.

3. **Build for production:**
   ```bash
   bun run build
   ```
   The built files will be in the `dist` directory.

4. **Preview the production build:**
   ```bash
   bun run preview
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
├── package.json           # Project dependencies and scripts
└── bun.lock               # Bun lockfile
```

## Features

- ⚡️ Fast development with Vite
- ⚛️ React 19 
- 🎨 Modern CSS with dark/light mode support
- 🔥 Hot Module Replacement (HMR)
- 📦 Optimized production builds

## Available Scripts

- `bun run dev` - Start development server
- `bun run build` - Build for production
- `bun run preview` - Preview production build locally