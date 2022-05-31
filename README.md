# devops-study-project-2-ci-cd
Private project to study DevOps tools and methodology (project idea from https://www.tutorialworks.com/devops-project-ideas)

Description from the above link: 

Project 2. Create and run a CI/CD pipeline for an app

Reliable delivery of software is one of the key tenets of DevOps; it’s one of the main reasons DevOps exists! So you need to know how to deliver software reliably through automation.

Gone are the days of pointing and clicking manually to deploy software. You should know how to set up a pipeline, using one of the popular tools.

Suggested steps

    1) Research and choose a CI/CD tool. You’ll want either a SaaS CI/CD service with a free tier you can use for learning, or a self-hosted tool. If you choose self-hosted, you’ll need to deploy the tool (extra credits if you do this!)
    2) Find a project on GitHub, preferably a web application so that you can interact with it using a web browser. We recommend Spring Petclinic which is a Java web application developed in Spring Boot, but use any other project you’re familiar with.
    3) Fork the project into your personal GitHub account.
    4) Write a pipeline for your CI/CD tool, to test, compile & package the application. Run the pipeline in the CI/CD tool.
    5) Extend the pipeline to deploy it to a server (this is the “CD” part). You’ll need to research to learn how the application is deployed.

For extra credits

    Add code quality checking. Add a stage to your pipeline which checks code quality, using Sonarqube or another open source or free tool.
    Add a manual approval stage. Add a stage to your pipeline which requires a manual approval before deploying to production.
    Deploy an app which comprises a separate frontend and backend (so, two pipelines)

Remember, you’ll need to use automation. No point-and-click allowed!

---
For these playbooks to work on your ansible control node you'll need: 
  ansible-core
  ansible-galaxy collections:
    - community.general
    - community.libvirt
  packages:
    - cloud-image-utils
  (to be continued)
---
