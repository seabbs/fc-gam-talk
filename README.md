
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


## Resources

Listed in no order. - some resources are free and some are not.

- [Datacamp GAM course](https://campus.datacamp.com/courses/nonlinear-modeling-in-r-with-gams)

- [Generalized Additive Models - An introduction with R by Simon Wood](people.maths.bris.ac.uk/~sw15190/igam/)

- [Flexible Regression and Smoothing - Using GAMLSS in R](https://www.crcpress.com/Flexible-Regression-and-Smoothing-Using-GAMLSS-in-R/Stasinopoulos-Rigby-Heller-Voudouris-Bastiani/p/book/9781138197909)

- [MGCV 2018 course](https://noamross.github.io/mgcv-esa-2018/)

-[From the bottom of the heap - GAM focussed blog](https://www.fromthebottomoftheheap.net)
