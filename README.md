# Visitor Tracker

This is a simple Node.js app that uses the Express.js framework and Redis to store and retrieve the number of visits to the app. The app is containerized using Docker and can be easily deployed using Docker Compose.

## Getting started

To get started with this app, you will need to have [Docker](https://www.docker.com/) and [Docker Compose](https://docs.docker.com/compose/) installed on your machine.

Clone this repository and navigate to the directory:
```bash
git clone https://github.com/Liranalb/visits.git
cd visits
```
Then, build and run the app using Docker Compose:
```bash
docker-compose up --build
```
This will start the Redis server and the Node.js app in separate containers. The app will be available at http://localhost:4001.

## Dependencies

This app has the following dependencies:

- [Express.js](https://expressjs.com/): A fast, minimalist web framework for Node.js
- [Redis](https://redis.io/): An in-memory data structure store, used for caching and real-time analytics

These dependencies are listed in the `package.json` file and can be installed using `npm install`.
