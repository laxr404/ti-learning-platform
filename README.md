# Template Injection Learning Platform
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
