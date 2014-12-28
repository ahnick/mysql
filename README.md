# About this Repo

This is a fork of the Git repo of the official Docker image for [mysql](https://registry.hub.docker.com/_/mysql/). 

The purpose of this repo is to remove the volumes from the official repo, so that the database can be committed as part of an image. This is intended to be used in a development environment scenario where you would want to push the docker image containing the database to a docker registry or the official docker hub.
