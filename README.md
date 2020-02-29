# Fortune
Displays a pseudorandom message from a database of quotations

## Fortun (Project Info)
[Website](https://en.wikipedia.org/wiki/Fortune_(Unix))

## Docker Hub
[Website](https://hub.docker.com/r/macabees/fortune/)

## Build image
`$ docker build -t macabees/fortune:latest .`

## Docker Push
`$ docker push -t macabees/fortune:latest`

Note: requires `docker login`

## Run image
`$ docker run -it --rm macabees/fortune`

--OR--

`$ docker run -it --rm macabees/fortune | docker run -i --rm macabees/cowsay --`
