# Description : Repository of a collection of Cloudformation templates which outline how to setup a highly available Jenkins build server deployed to Elasticbeanstalk with a Elastic file system.

## Author : Patrick Hynes

##Introduction

This repository is a set of cloudformation templates used to setup an highly available Jenkins Build Server (https://jenkins.io/) using a combination of Elastic Beanstsalk (http://docs.aws.amazon.com/elasticbeanstalk/latest/dg/Welcome.html) and the Elastic File System (http://docs.aws.amazon.com/efs/latest/ug/getting-started.html). The application deployed using the Jenkins Docker container listed on Dockerhub (https://hub.docker.com/r/jenkinsci/jenkins/)

## Repository Structure

The repository is broken down into folders corresponding to the different components of the infrastructure
* Elastic File System cloudformation templates
* Security Group cloudformation templates : Templates for the necessary security groups and instance profiles used by both the efs systems and the elasticbeanstalk ec2 instances in both environments (prod & dev)
* Jenkins Master Elastic Beanstalk cloudformation templates : Templates for the necessary EB apps and environments (prod & dev)
* Codecommit cloudformation templates : Creates the necessary Codecommit repositories

## Feedback

If you wish to contact me with feedback, please contact via email or skype

* @email: hynespm@gmail.com
* Skype: hynespm