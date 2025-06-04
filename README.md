# Java Web App Deployment with AWS CI/CD

Welcome to this project combining Java web app development and AWS CI/CD tools!

<br>

## Table of Contents
- [Introduction](#introduction)
- [Technologies](#technologies)
- [Setup](#setup)
- [Contact](#contact)
- [Conclusion](#conclusion)

<br>

## Introduction
This project is used for an introduction to creating and deploying a Java-based web app using AWS, especially their CI/CD tools.

The deployment pipeline I'm building around the Java web app in this repository is invisible to the end-user, but makes a big impact by automating the software release processes.

- I'm doing this project to learn more about CI/CD and get hands on experience in automating the flow from developing code to deployed web app. 
- This fits into my career goals because I want to become a DevOps engineer this year!

<br>

## Technologies & Tools
Here’s what I’m using for this project:

- **Amazon EC2**: I'm developing my web app on Amazon EC2 virtual servers, so that software development and deployment happens entirely on the cloud.
- Key pairs, SSH connections, Git, Maven and Java.
- **Key pairs**: Used to securely connect to the EC2 instance. Here--selected key pair: 'nextwork-keypair'. It's comprises of 2 keys: a public key that AWS keeps, and a private key.Once I set up my key pair, AWS automatically downloaded to my local computer the private key file format.pem (i.e Privacy Enhanced Mail) : nextwork-keypair.pem.
- **SSH connections**: SSH is a secure communication protocol that allows authorized users to access and control remote servers. I enabled SSH so that I can securely connect to my EC2 instance using the private key that matches the public key stored on the server.
- **Git**: A version control system that tracks changes with snapshots, making it easy to undo mistakes, collaborate, and push code to GitHub from a local repo.
- **Maven**: Apache Maven is a tool used to build and manage Java projects. It also acts as a package manager, automatically downloading any external libraries your project needs to run.
- **Java**: Java (version : Amazon Corretto 8 ) is a popular programming language used to build different types of applications, from mobile apps to large enterprise systems. It is required in this project because Maven depends on it to run and to generate the necessary files and templates/archetypes for our web app.
- **VS Code**: For my IDE, I chose Visual Studio Code. It connects directly to my development EC2 instance, making it easy to edit code and manage files in the cloud.
- **GitHub**: All my web app code is stored and versioned in this GitHub repository.
- **[COMING SOON] AWS CodeArtifact**: Once it's rolled out, CodeArtifact will store my artifacts and dependencies, which is great for high availability and speeding up my project's build process.
- **[COMING SOON] AWS CodeBuild**: Once it's rolled out, CodeBuild will take over my build process. It'll compile the source code, run tests, and produce ready-to-deploy software packages automatically.
- **[COMING SOON] AWS CodeDeploy**: Once it's rolled out, CodeDeploy will automate my deployment process across EC2 instances.
- **[COMING SOON] AWS CodePipeline**: Once it's rolled out, CodePipeline will automate the entire process from GitHub to CodeDeploy, integrating build, test, and deployment steps into one efficient workflow.


<br>

## Setup
To get this project up and running on your local machine, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/Cloud-HB/nextwork-web-project.git
    
    ```
2. Navigate to the project directory:
    ```bash
    cd nextwork-web-project
    ```
3. Install dependencies:
    ```bash
    mvn install
    ```

<br>

## Contact
!!! COMING SOON !!!: If you have any questions or comments about the my CI/CD project, please contact me on github directly:
Cloud-HB - [email@example.com](mailto:email@example.com)

- !!! COMING SOON !!!: [LinkedIn](https://www.linkedin.com/in/Cloud-HB-comming_soon/)

<br>

## Conclusion
Thank you for exploring this project! I'll continue to build this pipeline and apply my learnings to future projects.

A big shoutout to **[NextWork](https://learn.nextwork.org/app)** for their project guide and support. [You can get started with this DevOps series project too by clicking here.](https://learn.nextwork.org/projects/aws-devops-vscode?track=high)
