## Description : Elastic Beanstalk Environment configuration for Jenkins via Docker

## Author : Patrick Hynes

## Contact : hynespm@gmail.com

## Introduction

This project folder is for the deployment of Jenkins using Docker to an Elastic Beanstalk environment for Docker. The Dockerrun.aws.json file specifies the Jenkins image from Dockerhub. The .ebextensions folder specifies the mounting of the EFS system and also the restarting of the Docker daemon so that the Docker container is aware of the EFS mount.


## Feedback

If you wish to contact me with feedback, please contact via email or skype

* @email: hynespm@gmail.com
* Skype: hynespm