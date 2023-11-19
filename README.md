## Custom Docker Images

Cavelms is an E-learning platform. it includes a web application, services, and a website. The web app written in TypeScript and SvelteKit, while the services are written in Golang, and the website project is again built using TypeScript and SvelteKit.

## Setup the Development environment

First, clone the repository 
```bash
git clone https://github.com/onos9/dockerimages.git
```

Navigate to the project directory
```bash
cd dockerimages
```

run the database and backend services
```bash
docker compose up -d
```
