<center>

## The Software Supply Chain Stages

| [People](PEOPLE.md#people) | [Local Reqs](LOCAL.md#local-requirements) | [Source Code](CODE.md#source-code) | [Integration](INTEGRATION.md#continuous-integration) | [Deployment](DEPLOYMENT.md#continuous-deployment) | [Runtime](RUNTIME.md#runtime) | [Hardware](HARDWARE.md#hardware) | [DNS](DNS.md#dns)  | [Services](SERVICES.md#services) | [Cloud](CLOUD.md#cloud-resources)
| :---------: | :----------: | :--------------: | :-----------: | :------------------: | :-----------------: | :---------: | :------: | :----------------: | :---------:
|             |              |                  |               |                      |                     |             |          |                    |                 |
| Developers  | IDE          | Languages        | SCM providers | Build solutions      | Servers             | Embedded PC | URL      | SaaS solutions     | CDN             |
| QA team     | SCV          | Frameworks       | Pull requests | Deployment platforms | Operating systems   | PCB         | hostname | Third party APIs   | Cloud services  |
| DevOps team | Local tests  | Libraries        | Secrets mgmt  | Unit tests           | Webservers          | USB dongle  |          | Payment gateways   |                 |
|             | Git repos    | Package Managers |               | Functional tests     | Application servers | GPU/CPU     |          | Identity Providers |                 |
|             |              | Proprietary code |               | Security tests       | Web engines         |             |          | Analytics          |                 |
|             |              | Open source      |               | API test frameworks  | Databases           |             |          |                    |                 |
| [People](PEOPLE.md#people) | [Local Reqs](LOCAL.md#local-requirements) | [Source Code](CODE.md#source-code) | [Integration](INTEGRATION.md#continuous-integration) | [Deployment](DEPLOYMENT.md#continuous-deployment) | [Runtime](RUNTIME.md#runtime) | [Hardware](HARDWARE.md#hardware) | [DNS](DNS.md#dns)  | [Services](SERVICES.md#services) | [Cloud](CLOUD.md#cloud-resources)

</center>

## Continuous deployment

Continuous delivery is an extension of continuous integration that automatically deploys all code changes to a testing and/or production environment after the build stage. This means that in addition to automated testing, you have an automated release process, and can deploy your application at any time by clicking a button.

### What's in scope?

* Build servers
* Deployment platforms
* Security tests
* Functional tests

### Examples

<img src="images/azure-devops.svg" width="50" height="50" title="Azure DevOps">  <img src="images/jenkins.svg" width="50" height="50" title="Jenkins">  <img src="images/octopus-deploy.svg" width="50" height="50" title="Octopus Deploy"> <img src="images/buildkite.png" width="50" height="50" title="Buildkite">  <img src="images/bamboo.png" width="50" height="50" title="Atlassian Bamboo">

Bamboo, Selenium, Semgrep, SecureStack

### Who owns it?

* CloudOps team
* DevOps team

### What are the security concerns?

* Are disposable build environments secure?
* Are components being used during CI/CD known good? 
* Security scans are automated as part of the deployment process

### How do I secure it?

* Dynamic application security testing
* Static analysis security testing  
