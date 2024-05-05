## About
Aurora Ecosystem consists of 3 key elements:
1. Webpage [this repo](https://github.com/Aurora-195/AuroraWeb). The webpage is currently deployed at [https://auroratime.org](https://auroratime.org).
2. Server [this repo](https://github.com/Aurora-195/Backend)
3. Android Application [this repo](https://github.com/Aurora-195/AndroidHub)

## Demo Recording
Here's the [link to the project demo video](https://www.youtube.com/watch?v=G2c1-6Sg-GI)

## Project Specifics
Each repo has all the documentation and instructions on how to run it.

In order to make all the parts interact with each other - we had to deploy our backend to the AWS server, so Webpage and Android App can communicate with each other through the backend.
Because of this, running the Backend on a consumer machine will be a litte challenging (instruction are in the Server repo) and the functionality will be limited - the android application will not be able to connect to a locally run server for authentication.

The Webpage can be ran both locally (following the instruction on the webpage repo) or on a server (then it must be built inside Server's *client* folder so the server can serve the React files).

The Server is currently deployed to AWS and serves the Webpage files and backend logic. The Webpage can be accessed at [https://auroratime.org](https://auroratime.org).


