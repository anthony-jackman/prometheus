# PROMETHEUS

A backend for online education tracking, both the development thereof and production environments.

## What's in a word

In Greek mythology, Prometheus is a Titan god of fire. Prometheus is best known for defying the gods by stealing fire from tehm and giving it to humanity in the form of technology, knowledge, and more generally, civilization.

## Badges
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## Features

- OpenAPI specs
- Fast!

## Contributing to my project

Contributions always welcomed! See [CONTRIBUTING.md] for ways to get started.  Please adhere to this project's [Code of Conduct](https://github.com/anthony-jackman/prometheus/.github/CODE_OF_CONDUCT.md).

## Documentation

The project [documentation] and more importantly the Application Programming Interface (API) [Reference] can be found in these locations.

## Authors and Contributors

- [@energeticpixels](https://github.com/EnergeticPixels): Coding

## Installation
This API is built and maintained under the idea that NGINX to provide reverse proxy, secure socket layer (SSL/TLS) to the outside world, firewalls, application monitoring, and PM2 instance.  After that, 
```bash
    npm install
    pm2 start
```

## Running in Development Mode
- Clone the project from Github into a working folder of your choosing.
- cd into that working folder 
```bash
    npm install
    npm dev
```
This is an API, so there will be no 'front-end' or visual component.  You will interface in development either through built-in tests or through an utility like Postman.  Refer to the API reference mentioned above on end points to reach out to.

## Running Test
```bash
    npm run test
```

## Tech Stack

**Server**: Node, Fastify version 4

**Data Persistance**: MongoDB
