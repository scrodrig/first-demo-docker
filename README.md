# Basic Express Server with Docker

This project demonstrates how to set up a basic Express server and run it using Docker.

## Prerequisites

- Docker installed on your machine
- Node.js and npm installed

## Project Structure

```
.
├── Dockerfile
├── package.json
├── app.mjs
└── helper.mjs
```

## Building and Running the Docker Container

1. Build the Docker image:

   ```sh
   docker build -t basic-express-server .
   ```

2. Run the Docker container:

   ```sh
   docker run -p 3000:3000 basic-express-server
   ```

3. Open your browser and navigate to `http://localhost:3000` to see the "Hi there!" message.

## License

This project is licensed under the MIT License.