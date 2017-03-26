# dockerized-docs-ovirt

# What is it? #
Dockerzied ovirt.org site + ovirt documentation for offline use.

# Image description #
- Base image: `ruby:latest`.
- The most current ovirt-site `master` branch is cloned.
- Middleman is installed using bundle.

# How to use this image #

```console
$ docker run -d genadipost/dockerized-docs-ovirt

```

You can test it by visiting http://container-ip:4567
