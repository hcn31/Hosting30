# Hosting30
This repository contains a sample React Native project that communicates with an Express backend and MongoDB, both running in Docker containers.

## Prerequisites

Before you begin, ensure you have the following software installed on your machine:

- Docker: [Install Docker](https://docs.docker.com/get-docker/)
- Node.js: [Install Node.js](https://nodejs.org/)

## Getting Started

1. Clone the repository:

```bash
git clone [https://github.com/your-username/your-react-native-project.git](https://github.com/hcn31/Projet-React-Native.git)
```
2. install the dependencies

then go to the react native project on the root run the command to install the dependencies:
```bash
npm install
```
3. set up the docker enironment

go into the express project in the root run the following commands:
```bash
docker-compose build
docker-compose up -d
```
Please check in docker that the containers are set up and running correctly


4. run the app
in react native project to start the project run the command:
```bash
npm start
```



