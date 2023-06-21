<center>

## The Software Supply Chain Stages

| [People](PEOPLE.md) | [Local Reqs](LOCAL.md) | [Source Code](CODE.md) | [Integration](INTEGRATION.md) | [Deployment](DEPLOYMENT.md) | [Runtime](RUNTIME.md) | [Hardware](HARDWARE.md) | [DNS](DNS.md) | [Services](SERVICES.md) | [Cloud](CLOUD.md)
| :---------: | :----------: | :--------------: | :-----------: | :------------------: | :-----------------: | :---------: | :------: | :----------------: | :---------:
| Developers  | IDE          | Languages        | Git repos     | Build solutions      | Servers             | Embedded PC | URL      | SaaS solutions     | CDN             |
| QA team     | SCV          | Frameworks       | SCM providers | Deployment platforms | Operating systems   | PCB         | hostname | Third party APIs   | Cloud services  |
| DevOps team | Local tests  | Libraries        | Pull requests | Unit tests           | Webservers          | USB dongle  |          | Payment gateways   |                 |
|             |              | Package Managers | Secrets mgmt  | Functional tests     | Application servers | GPU/CPU     |          | Identity Providers |                 |
|             |              | Proprietary code |               | Security tests       | Web engines         |             |          | Analytics          |                 |
|             |              | Open source      |               | API test frameworks  | Databases           |             |          |                    |                 |
| [People](PEOPLE.md) | [Local Reqs](LOCAL.md) | [Source Code](CODE.md) | [Integration](INTEGRATION.md) | [Deployment](DEPLOYMENT.md) | [Runtime](RUNTIME.md) | [Hardware](HARDWARE.md) | [DNS](DNS.md) | [Services](SERVICES.md) | [Cloud](CLOUD.md)

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

