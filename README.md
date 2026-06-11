# Travel Planner

A travel planner web app built as the capstone project for the Udacity Front End Web Developer Nanodegree.

Enter a destination and a travel date, and the app shows:

- A countdown of how many days until your trip
- A trip summary (city, country, departure date)
- The weather forecast for your destination
- A representative photo of the destination

It combines several external APIs:

- **Geonames** – looks up coordinates for the destination
- **Dark Sky** – fetches the weather forecast (proxied through the Express server)
- **Pixabay** – pulls a photo of the destination (falls back to a country photo for rural locations)

## Tech Stack

- JavaScript (ES6) bundled with Webpack
- Sass for styling
- Express + Node.js backend
- Jest for testing
- Service Worker for offline support

## Getting Started

Install dependencies:

```bash
npm install
```

Build and run the app:

```bash
npm run build-prod
npm run start
```

The app runs on `http://localhost:1015/`.

For development mode:

```bash
npm run build-dev
```

To run the tests:

```bash
npm run test
```
