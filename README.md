# Table of content
[DockerizingQaEnv](https://github.com/niyogv/DockerizingQaEnv/blob/main/README.md#dockerizingqaenv)

[How it works?](https://github.com/niyogv/DockerizingQaEnv/blob/main/README.md#how-it-works)

# About the project
The project which here used is iome(moi-id)
![Screenshot 2024-01-03 at 12 21 09 PM](https://github.com/niyogv/DockerizingQaEnv/assets/77136963/f7dc62b3-d2b9-4263-9611-8b59230e3b30)

# Why dockerizing the qa env
**Consistency Across Environments:**
Docker containers encapsulate the entire environment, including application code, dependencies, and configurations. This ensures consistency in the QA environment.

**Isolation and Reproducibility:**
Docker containers provide isolation, allowing you to package an application and its dependencies into a self-contained unit. This isolation ensures that the QA environment is reproducible, meaning that it can be easily recreated on different machines or by different team members.

**Scalability and Parallel Testing:**
Docker enables the easy creation of multiple containers running different instances of the QA environment. This is especially beneficial for running parallel tests, as each container can represent a separate test environment. This can significantly speed up testing workflows.

**Versioning and Rollback:**
Docker images can be versioned, providing a mechanism for rolling back to previous versions of the QA environment if needed. This can be valuable for troubleshooting issues or for ensuring consistency across different stages of the development lifecycle.

**Collaboration and Onboarding:**
Dockerized QA environments make it easier for new team members to get started with testing. They can simply pull the Docker image and have a fully functional QA environment without dealing with complex installation and configuration steps.

**Easier Integration with CI/CD Pipelines:**
Docker integrates well with Continuous Integration/Continuous Deployment (CI/CD) pipelines. Dockerized QA environments can be easily incorporated into automated testing workflows, ensuring that tests are run in consistent environments before code is deployed.


# DockerizingQaEnv
This is the example docker file to containerizing the qa env to perfom the smoke test using different base image

# How it works?
1.Here in this file we used base image as ubuntu

2.Install dependencies as required

3.Install chrome and chrome driver for the executaion of the python application

4.Install python dependencies like selenium, pytest and python to perform automation testing


