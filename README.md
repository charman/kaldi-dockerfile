# Dockerfile for Kaldi

This repo contains a Dockerfile for building the latest version of
Kaldi from GitHub.

As of 2017-05, it is not possible to create a Docker Hub automated
build for Kaldi because compiling Kaldi takes too long.  Docker Hub
automated builds currently use a single CPU with 2GB of RAM, and
builds time out if compilation takes more than two hours.
