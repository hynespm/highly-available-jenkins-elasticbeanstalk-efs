## Description : Cloudformation template for an Elastic Beanstalk Application that supports the Docker platform. The EC2 Instances are spread across two AZ's

## Author : Patrick Hynes

## Contact : hynespm@gmail.com

##Introduction

The cloudformation template creates an elastic beanstalk application and two environments spread across two AZ's. They are initially created with the sample docker application. This template requires that the necessary VPC structure is created and that the VPC-Id and the Subnet Id's are exported so that they can be referenced within this template. The pre-requisites are listed below.


## Prerequisites : 

* VPC-Id (VPC-Id)
* Subnet Id in one Az (VPC-AZ1-Id)
* Subnet Id in a second Az (VPC-AZ2-Id)


## Feedback

If you wish to contact me with feedback, please contact via email or skype

* @email: hynespm@gmail.com
* Skype: hynespm

