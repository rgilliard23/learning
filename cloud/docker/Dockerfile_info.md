# Docker file


## Summary
### The dockerfile defines the layers of an image
_____
## Definining Layers

FROM pulls the "parentimage"

COPY pulls the source code that we want to use | COPY . .

RUN instruction tells the image to run a command on in the image itself

WORKDIR tells the image where to run the subsequent commands on the image

CMD tells the image what commands to run at runtime (after the image is created)

EXPOSE tells the image what port to expose



