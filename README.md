# docker-base

Creates an Ubuntu base docker images. This is a foundational Docker image that
will be used to create other Docker images, mostly node.js projects.
Features
- node.js v10 & npm
- git, curl
- non-sudo global installs with npm (like on a mac)
