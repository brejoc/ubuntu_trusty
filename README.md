# ubuntu_trusty Docker image

This docker image of Ubuntu 14.04 is used as a build image for [drone.io](http://drone.io/). drone needs git pre-installed, so this is the most prominent change - and we're usually building python (2.7) projects.