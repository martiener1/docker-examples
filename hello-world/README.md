# Hello World!

This is a quick example of a python script running inside a docker container.

## Build the image

Open a terminal on the this directory and run the following command:

```shell
docker build -t hello-world ./hello-world
```

This will use the Dockerfile inside the `/hello-world` directory to build an image.

`docker build` is the command to build an image.

`-t hello-world` gives the image a name so it can be referenced later.

`./hello-world` is location of the `Dockerfile`, this tells docker what to build.

## Run the container

Use the same terminal from previous step and run the following command:

```shell
docker run hello-world -rm
```

`docker run` is the command to run a container.

`hello-world` is the name of the image that we created in the previous step.

`-rm` removes the container and it's data after it stops running. This prevents you from filling up your disk with rubbish. 
