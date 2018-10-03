
GAMs - sorry you mean GLM?
==========================

This repository contains a talk introducing Generalised Additive Models and their applications in R. Feel free to make use of the provided docker container as a starting point for your own analysis.

Docker
------

This repository contains a docker file based on the [`rocker\tidyverse`](https://hub.docker.com/r/rocker/tidyverse/) docker image. Run the following in the command line (with an active [docker](https://docs.docker.com/install/) installation running) to pull and run the container.

``` r
## Pull the container
docker pull seabbs/fc-gam-talk

docker run -d -p 8888:8787 -e USER=gam -e PASSWORD=gam --name gam seabbs/fc-gam-talk
```

The Rstudio server will be found at `localhost:8888`, sign in using the username gam and the password gam.
