# A container for the Spyder IDE! [![Images](https://github.com/JasperBakker1/spyder_container/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/JasperBakker1/spyder_container/actions/workflows/docker-publish.yml)
This container includes the Spyder IDE installed in a conda container together with some often used conda/python packages. 

The container is intended for use in distrobox/toolbox, but can of course be used to your own liking!❤️

Use this container by running:
```
$ distrobox-assemble create --file https://raw.githubusercontent.com/JasperBakker1/spyder_container/refs/heads/master/[container type]_container.ini
```
on your local Linux system for the base image.
