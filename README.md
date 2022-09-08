# Digital Health code-night: guides and examples

This Github repository is an example repository for showing how you quickly can get started working on a full-stack software application that uses data from open and free APIs for the health care domain. The repository is created for the CoCoders & Trifork code-night event on September 21st, 2022.

## Focus areas

The focus areas of the code-night event is for you to create your own Github repository, where you can place your source code for your project. A personal Github repository is a great way to show others what you are currently working on in your sparetime, but also which technologies you have experience with or are interested in.

The code-night will focus on Digital Health IT-solutions and show you how you can take advandtage of open health APIs in your application in order to have data to work with. 

Another focus area of the event is to show how software systems, large or small, business critical or home projects, are built up. 
Usually, you will need a database to store data, a backend layer to get data from the database and forward the data to a front-end application such as a mobile app or a web page. You will also need to get the data from somewhere, and here the concept of an API comes in place. 
You will need to look at an API definition and implement code that talks to this API to get the data you want.
Last but not least, your applications need to run somewhere, and here the cloud will be introduced. The concept of having a cloud to take care of running your services is great if you want to get started quickly. You don't have to worry about how and where to run your services. In this project we will use the AWS cloud as an example.

You will probably not be able to finish all areas of the challenges given at the code-night, but you can continue at home and build more to your application later on, in order to be able to have a full software system running.

When the code night is over, you will hopefully have a better understanding of the SST framework, which we will use at the code-night and how to interact with APIs in general.

During the code-night, you can work in groups or alone, it's up to you, and you can share your code with others, get inspiration and help by talking to others or other groups during the event.

## Prerequisites

At this code-night we will be using [SST](https://sst.dev/) which is a great framework for creating and deploying full-stack serverless applications in the cloud in no time. 

You need to download and install the tools mentioned in the [SST getting started guide](https://docs.sst.dev/quick-start). 

 - Step 1: You need a Github account. If you don't have one already, [sign up here](https://github.com/).
 
 - Step 2: Download and install [Node.js](https://nodejs.org/en/download/) on your computer.

 - Step 3: Create a free-tier Amazon Web Services (AWS) [account](https://sst.dev/chapters/create-an-aws-account.html).
 
 - Step 4: Install the [AWS CLI](https://sst.dev/chapters/configure-the-aws-cli.html) locally on your computer.
 
 - Step 5: Use your favourite IDE to work on your software applications. For example, download [Visual Studie Code](https://code.visualstudio.com/download) IDE.


## Programming language

You can use the programming languages of your choice in your project, since the SST framework supports various languages. So choose the language you are most familiar with.

 - Java
 - Go
 - Typescript
 - Python
 - ...

## Open APIs for health care data

There are several open and free APIs available for getting health care data, which you can retrieve and use in your project. 

The list of public APIs can be seen here:

https://github.com/public-apis/public-apis#health

In the `src` folder in this Github repository, there is an example of how to use a REST based API for getting health care data in your application.

## Challenges

TODO!!! In the `src` folder there will be example code snippets of some of the challenges described in the following, but you can also start from scratch and create applications by yourself and connect to an API of your choice:

We will describe the coding challenges that you will start with and work on during this code-night. You will probably not have enough time to work on all challenges described here, but there is plenty of content in the guides to continue at home and finish the projects you have started at the code-night.

1. The first part of the code-night is to download and install the prerequisites, if you have not done that prior to the code-night. 

2. Next, start the tutorial in the SST start-up guide in order to get a simple application up and running in AWS.

3. Implement a REST service that can get data from one of the open and free APIs for health care data, and choose which API you want to use.

4. Implement a front-end application in SST where you can show and display the health care data directly. 
You can choose to use time and energy on the design and the user experience of the app. 

5. Focus more on implementing the back-end service, that stores data in a simple database (again by using the SST framework).

6. You can also choose to manipulate the health care data that you get from the REST API.

7. Be sure to document your project, what is does and what it shows, and how to run it, in the README file of your personal Github repo.





