# Maven Starter
Starter code to configure your project to CircleCI if you are using Maven.

Config file setup from: https://circleci.com/docs/2.0/language-java-maven/

## Getting started with CircleCI

We will be using CircleCI for our CI/CD pipeline in this course. This repository contains the configuration you will need to get started with CircleCI. 

You will need to [set up an account with CircleCI](https://circleci.com/signup/). The easiest way to sign up is to do so through your GitHub account. 

You will be prompted to grant CircleCI access to your public and private repositories, as well as your email address. Access to public and private repositories enables CircleCI to run the CI/CD pipeline. Your email address is used to send you email notifications about build status (when something fails or succeeds). If you are concerned about granting this level of access to existing projects on your GitHub account, you can create a new GitHub account for this course. 

![OAuth Screen](https://imagesgpscourses.s3.amazonaws.com/Screen+Shot+2019-09-27+at+9.18.28+AM.png)

Click "Authorize circleci," which will direct you to your CircleCI dashboard. 

From your Dashboard, you can choose which projects you'd like to use with CircleCI. If you haven't added anything to this repository yet, you won't have anything to test at this point. (If you add this project without any additional code, your build will fail.)

Once you get your project up and running, you can check back into your dashboard and add this repository to your jobs. CircleCI will then run a build and provide information about the build status to you. Be sure to read the build logs for useful information about errors. 