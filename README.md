Welcome to Sasi-IDE website
===========================

This website is deployed in AWS CodeStar project to an Amazon EC2 instance.

## What's Here?
This code includes:

* README.md - this file
* appspec.yml - this file is used by AWS CodeDeploy when deploying the website
  to EC2
* scripts/ - this directory contains scripts used by AWS CodeDeploy when
  installing and deploying the website on the Amazon EC2 instance
* webpage/ - this directory contains static web assets used by the website
  * index.html - this file contains the website main page
  * js/ - this directory contains javascript/jquery code used by the website
  * css/ - this directory contains stylesheets used by the website
* template.yml - this file contains the description of AWS resources used by AWS
  CloudFormation to deploy the infrastructure
* template-configuration.json - this file contains the project ARN with placeholders used for tagging resources with the project ID

## About
[**Sasi IDE**](http://ec2-3-132-109-231.us-east-2.compute.amazonaws.com) is a free and open-source online code editor that allows you to write and execute code from a rich set of languages. It's perfect for anybody who just wants to quickly write and run some code without opening a full-featured IDE on their computer. Moreover, it is also useful for teaching and learning or just trying out a new language.

## APIs Used
Sasi IDE is using below APIs from [**Judge0 Rapid APIs**](https://rapidapi.com/hermanzdosilovic/api/judge0) for executing user's source code.
1. [GET]  Get a Submission
2. [POST] Create a Submission
