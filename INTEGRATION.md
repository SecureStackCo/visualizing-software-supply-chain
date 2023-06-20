# Visualizing the Software Supply Chain

The software supply chain is under increasing threat.  New attacks and threats have popped up that we couldn't have imagined even two years ago.  Total attacks on the software supply chain are increasing by more than [730% year on year since 2019](https://portswigger.net/daily-swig/researchers-find-633-increase-in-cyber-attacks-aimed-at-open-source-repositories)

Unfortunately, there is no consistent agreement on what is in the software supply chain. This is a problem as we can't secure the software supply chain if we don't know what's in it.  This project aims to help fix that by giving people a visual and contextual way to understand what specific components are in a particular software supply chain.  If you want to tag your own components you can fork this repo and edit it to suit your specific software supply chain profiles. 

![Visualizing the Software Supply Chain](images/Software-Supply-Chain-Visualization.png)

<center>

## The Software Supply Chain Stages

| [People](PEOPLE.md) | [Local Reqs](LOCAL.md) | [Source Code](CODE.md) | [Integration](INTEGRATION.md) | [Deployment](DEPLOYMENT.md) | [Runtime](RUNTIME.md) | [Hardware](HARDWARE.md) | [DNS](DNS.md)  | [Services](SERVICES.md) | [Cloud](CLOUD.md)
| :---------: | :----------: | :--------------: | :-----------: | :------------------: | :-----------------: | :---------: | :------: | :----------------: | :---------:
|             |              |                  |               |                      |                     |             |          |                    |                 |
| Developers  | IDE          | Languages        | Git repos     | Build solutions      | Servers             | Embedded PC | URL      | SaaS solutions     | CDN             |
| QA team     | SCV          | Frameworks       | SCM providers | Deployment platforms | Operating systems   | PCB         | hostname | Third party APIs   | Cloud services  |
| DevOps team | Local tests  | Libraries        | Pull requests | Unit tests           | Webservers          | USB dongle  |          | Payment gateways   |                 |
|             |              | Open source      |               | Functional tests     | Application servers | GPU/CPU     |          | Identity Providers |                 |
|             |              | Proprietary code |               | Security tests       | Web engines         |             |          | Analytics          |                 |
|             |              |                  |               |                      | Databases           |             |          |                    |                 |
| [People](PEOPLE.md) | [Local Reqs](LOCAL.md) | [Source Code](CODE.md) | [Integration](INTEGRATION.md) | [Deployment](DEPLOYMENT.md) | [Runtime](RUNTIME.md) | [Hardware](HARDWARE.md) | [DNS](DNS.md)  | [Services](SERVICES.md) | [Cloud](CLOUD.md)

</center>

## Continuous Integration

Continuous integration (CI) is the process of automatically integrating code changes from multiple contributors into a single software project. This is an important DevOps best practice that enables developers to frequently merge code changes into a central repository for testing before deployment. Automated tools are used to check that the new code is correct before integration.

### What's in scope?

* SCM providers
* Pull requests

### Examples

#### SCM Providers

<img src="images/github.svg" width="50" height="50" title="GitHub">  <img src="images/bitbucket.svg" width="50" height="50" title="Bitbucket">  <img src="images/azure-repos.png" width="50" height="50" title="Azure Repos"> <img src="images/gitlab.svg" width="50" height="50" title="GitLab">  <img src="images/gitea.png" width="50" height="50" title="Gitea">  <img src="images/codecommit.png" width="50" height="50" title="CodeCommit">

