# Creating a Continuous Delivery Pipeline with AWS

This repository contains a sample Node.js web application built using [Express](https://expressjs.com/), meant to be used as part of the AWS DevOps Learning Path.

# Overview

I have created a continuous delivery pipeline for a simple web application. I have first use a version control system to store my source code. Then i have create a continuous delivery pipeline that will automatically deploy my web application whenever source code is updated.

# Accomplish

Steps to create the continuous delivery pipeline.
- Set up a GitHub repository for the application code
- Create an AWS Elastic Beanstalk environment to deploy the      application
- Configure AWS CodeBuild to build the source code from GitHub
- AWS CodePipeline to set up the continuous delivery pipeline with source, build, and deploy stages.

# Application architecture

The following diagram provides a visual representation of the services used and how they are connected. This application uses GitHub, AWS Elastic Beanstalk, AWS CodeBuild, and AWS CodePipeline.



# Screenshots

https://drive.google.com/file/d/1csYPdrdIMRx9kmaV6rZe50Wq4v15jpKF/view?usp=sharing

## Acknowledgements

 - [AWS Hands-on Practice]( https://aws.amazon.com/getting-started/hands-on/create-continuous-delivery-pipeline/ )
 - [ AWS Documentation ]( https://docs.aws.amazon.com/ )


# Authors

- [@Rakesh kumar](https://github.com/Rakesh709)


# Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

# License

This library is licensed under the MIT-0 License. See the LICENSE file.

