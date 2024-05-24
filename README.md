# Template Injection Learning Platform

The Template Injection Learning Platform was made to introduce the topic of template
injection to a new audience. The focus is to serve as a tool for visual and interactive
learning. 

The platform is also available on GitHub Pages to remove
access barriers to the theory and tools within. The public page will not have any
challenges available for security reasons. The full version is available in this
repository and it will be necessary to download the repository and host it locally, to run
a challenge.

This platform was developed as part of my bachelor's thesis and I aim to maintain it for the foreseeable future.

- Access [Public Page](https://laxr404.github.io/ti-learning-platform-public/) for easy perusal.
- Access [Public Page Repository](https://github.com/laxr404/ti-learning-platform-public/).

## Features
- Fundamentals are explained in a simple, easy-to-understand manner with visual help.
- Tools are provided to deepen knowledge on template injection and apply the theory.
- Research results are shown in tables.
- An Interactive Decision Tree helps users apply research practically.
- Attack Labs offer (for now) simple challenges to practice learned basics in a safe environment.

## Prerequisites
- Install [Docker Compose](https://docs.docker.com/compose/install/).
- Download or clone this repository.

## Usage
1. Build the servers *(only needed at first launch or when changes have been made)*: `docker compose build`
2. Start the servers and the playground: `docker compose up` or use: `sudo docker-compose up --build -d`
3. Access the platform at [http://127.0.0.1](http://127.0.0.1)
4. Close the platform: `docker compose down`

## Troubleshooting
- When there are permission errors upon starting or building the docker compose, try adjusting the rights: `chmod 755 -R ti_platform`
- Incorrect Docker Compose installations may cause errors when trying to start up the platform. Make sure to follow each step accurately.

## License
- The Template Injection Learning Platform is licensed under the Apache License, Version 2.0.
