# Zomato Clone

A React-based restaurant discovery and food ordering landing page inspired by Zomato. This project recreates the look and feel of a modern food delivery platform with sections for restaurant cards, trending collections, city highlights, promotional calls-to-action, and a footer with app information.

## Project Overview

This application is designed as a front-end clone of Zomato's homepage experience. It includes:

- A responsive header/navigation bar
- Restaurant and food category cards
- Collections section for popular dining experiences
- City-based browsing blocks
- Promotional app CTA section
- Account/app info panels
- Footer with site links and branding

## Tech Stack

- React.js
- Create React App
- Sass (SCSS)
- Material UI components
- JavaScript

## Features

- Modern single-page UI inspired by Zomato
- Reusable component-based structure
- Clean and responsive layout
- Styled cards and sections for food discovery
- Built for rapid front-end prototyping and UI design iteration

## Project Structure

```bash
.
├── public/
├── src/
│   ├── components/
│   ├── App.js
│   ├── app.scss
│   ├── index.js
│   └── ...
├── Dockerfile
├── package.json
├── package-lock.json
├── README.md
└── .github/
```

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Node.js (v18 or later recommended)
- npm

### Installation

```bash
npm install
```

### Run the app locally

```bash
npm start
```

This will start the development server and open the app in your browser at:

```text
http://localhost:3000
```

### Production build

```bash
npm run build
```

This creates an optimized production build in the `build` folder.

## Docker Support

A `Dockerfile` is included for containerized runs if you want to build and run the project in a Docker environment.

Example:

```bash
docker build -t zomato-clone .
docker run -p 3000:3000 zomato-clone
```

## Notes

This project is primarily a UI clone and front-end practice repository. It focuses on visual structure and user experience rather than full backend integration or live restaurant data.

## License

This project is for educational and portfolio demonstration purposes.
