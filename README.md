# docker-base

Creates an Ubuntu base docker images. This is a foundational Docker image that
will be used to create other Docker images, mostly node.js projects.
Features
- Ubuntu 20.04 focal
- node.js v14 & npm
- git, curl, wget
- non-sudo global installs with npm (like on a mac)
