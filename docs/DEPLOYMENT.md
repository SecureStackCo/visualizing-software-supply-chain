<center>

## The Software Supply Chain Stages

| [People](docs/PEOPLE.md) | [Local Reqs](docs/LOCAL.md) | [Source Code](docs/CODE.md) | [Integration](docs/INTEGRATION.md) | [Deployment](docs/DEPLOYMENT.md) | [Runtime](docs/RUNTIME.md) | [Hardware](docs/HARDWARE.md) | [DNS](docs/DNS.md)  | [Services](docs/SERVICES.md) | [Cloud](docs/CLOUD.md)
| :---------: | :----------: | :--------------: | :-----------: | :------------------: | :-----------------: | :---------: | :------: | :----------------: | :---------:
|             |              |                  |               |                      |                     |             |          |                    |                 |
| Developers  | IDE          | Languages        | SCM providers | Build solutions      | Servers             | Embedded PC | URL      | SaaS solutions     | CDN             |
| QA team     | SCV          | Frameworks       | Pull requests | Deployment platforms | Operating systems   | PCB         | hostname | Third party APIs   | Cloud services  |
| DevOps team | Local tests  | Libraries        | Secrets mgmt  | Unit tests           | Webservers          | USB dongle  |          | Payment gateways   |                 |
|             | Git repos    | Package Managers |               | Functional tests     | Application servers | GPU/CPU     |          | Identity Providers |                 |
|             |              | Proprietary code |               | Security tests       | Web engines         |             |          | Analytics          |                 |
|             |              | Open source      |               | API test frameworks  | Databases           |             |          |                    |                 |
| [People](docs/PEOPLE.md) | [Local Reqs](docs/LOCAL.md) | [Source Code](docs/CODE.md) | [Integration](docs/INTEGRATION.md) | [Deployment](docs/DEPLOYMENT.md) | [Runtime](docs/RUNTIME.md) | [Hardware](docs/HARDWARE.md) | [DNS](docs/DNS.md)  | [Services](docs/SERVICES.md) | [Cloud](docs/CLOUD.md)

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

### How do I secure it?

* 
