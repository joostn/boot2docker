This is my fork of [boot2docker](https://github.com/boot2docker/boot2docker)

- added kernel modules necessary for strongswan (kernel-config.d/strongswan)
- added nano text editor

To build the iso:

```docker build -t boot2docker . && docker run --rm boot2docker > boot2docker.iso```
