# Stopwatch

A clean, modern stopwatch application built with React and TypeScript.

## Overview

This is a basic stopwatch web application that provides essential stopwatch functionality with a user-friendly interface. The app is built using modern web technologies and can be deployed locally or via Docker.

## Tech Stack

- **React** - UI framework for building interactive interfaces
- **TypeScript** - Type-safe JavaScript for robust development
- **Vite** - Fast build tool and development server
- **React Router** - Client-side routing
- **Docker** - Containerization for easy deployment

## Project Structure

```
.
├── app/                      # Application source code
├── public/                   # Static assets
├── package.json              # Project dependencies and scripts
├── vite.config.ts            # Vite build configuration
├── react-router.config.ts    # React Router configuration
├── tsconfig.json             # TypeScript configuration
├── Dockerfile                # Docker configuration for containerization
└── README.md                 # This file
```

## Getting Started

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/GabrielZub0vsky/Stopwatch.git
   cd Stopwatch
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

### Development

To run the development server:

```bash
npm run dev
```

The application will be available at `http://localhost:5173` (or another port shown in your terminal).

### Build

To build the application for production:

```bash
npm run build
```

### Docker

To run the application in a Docker container:

1. Build the Docker image:
   ```bash
   docker build -t stopwatch .
   ```

2. Run the container:
   ```bash
   docker run -p 3000:3000 stopwatch
   ```

## Features

- Start, stop, and reset stopwatch functionality
- Clean and intuitive user interface
- Built with modern React best practices
- Type-safe with TypeScript

## License

This project is currently unlicensed. See the repository for more information.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve the application.

---

Created by [GabrielZub0vsky](https://github.com/GabrielZub0vsky)
