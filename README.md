# aws-ecs-codepipeline

This is a simple train schedule app written using nodejs.

## Running the app on the terminal

You need a Java JDK 7 or later and Gradle to run the build. You can run the build like this:

    gradle build

You can run the app with:

    gradle npm_start

Once it is running, you can access it in a browser at http://localhost:8080

## Running the app with Docker

You need to create the Docker image

    docker build -t nodejs .

You can run the container with:

    docker-compose up &

Once it is running, you can access it in a browser at http://localhost:8080
