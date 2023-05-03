### Technologies

Volta: https://docs.volta.sh/guide/#why-volta

pnpm: https://pnpm.io/installation

swc (Rust-based platform for the Web): https://swc.rs/

morgan: (HTTP request logger middleware for node.js): https://www.npmjs.com/package/morgan

Dockerfile: tells us how to build our node image

### VSCode Extensions

Trigger Task on Save

### Running Docker

`docker compose up` starts up all of the services in the docker-compose.yml file. The backend service
builds the current directory from the Dockerfile.

Docker starts by building the node 18 base image than
it goes line by line through the Dockerfile following each of the steps provided.
