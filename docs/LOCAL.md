<center>

## The Software Supply Chain Stages

| [People](PEOPLE.md#people) | [Local Reqs](LOCAL.md#local-requirements) | [Source Code](CODE.md#source-code) | [Integration](INTEGRATION.md#continuous-integration) | [Deployment](DEPLOYMENT.md#continuous-deployment) | [Runtime](RUNTIME.md#runtime) | [Hardware](HARDWARE.md#hardware) | [DNS](DNS.md#dns) | [Services](SERVICES.md#services) | [Cloud](CLOUD.md#cloud-resources)
| :---------: | :----------: | :--------------: | :-----------: | :------------------: | :-----------------: | :---------: | :------: | :----------------: | :---------:
|             |               |                  |               |                      |                     |             |          |                    |                 |
| Developers  | IDE           | Languages        | SCM providers | Build solutions      | Servers             | Embedded PC | URL      | SaaS solutions     | CDN             |
| QA team     | SCV           | Frameworks       | Pull requests | Deployment platforms | Operating systems   | PCB         | hostname | Third party APIs   | Cloud services  |
| DevOps team | Local tests   | Libraries        | Secrets mgmt  | Releases             | Webservers          | USB dongle  |          | Payment gateways   |                 |
| Package Maintainers | Git repos     | Package Managers | Git repos     | Functional tests     | Application servers | GPU/CPU     |          | Identity Providers |                 |
|             | Page Builders | Packages         |               | Security tests       | Web engines         |             |          | Analytics          |                 |
|             |               | Open source      |               | API test frameworks  | Databases           |             |          | Proxies            |                 |
|             |               | Proprietary Code |               | Unit tests           |                     |             |          |                    |                 |
|             |               |                  |               |                      |                     |             |          |                    |                 |
| [People](PEOPLE.md#people) | [Local Reqs](LOCAL.md#local-requirements) | [Source Code](CODE.md#source-code) | [Integration](INTEGRATION.md#continuous-integration) | [Deployment](DEPLOYMENT.md#continuous-deployment) | [Runtime](RUNTIME.md#runtime) | [Hardware](HARDWARE.md#hardware) | [DNS](DNS.md#dns) | [Services](SERVICES.md#services) | [Cloud](CLOUD.md#cloud-resources)

</center>

## Local Requirements 

This includes any local applications, configurations, or other dependencies that are needed to for the people building software to successfully do their job.

### What's in scope?

* IDE
* Source code versioning tools
* Local tests
* Local git repositories
* Page builders

### Examples

#### IDE

<img src="images/vscode.png" width="50" height="50" title="VS Code">  <img src="images/atom.png" width="50" height="50" title="Atom">  <img src="images/vim.png" width="50" height="50" title="Vim">

#### SCV Tools

<img src="images/git.svg" width="50" height="50" title="Git">  <img src="images/mercurial.png" width="50" height="50" title="Mercurial">  <img src="images/clearcase.png" width="50" height="50" title="Clearcase">

#### Local tests

Linting, static analysis, software composition analysis

#### Local git repositories

Source code stored on devs laptop, private packages, install scripts, deployment scripts

### Who owns it?

* Individual engineers

### What are the security concerns?

* Choice of tools has different security outcomes
* Git has several local security features which are typically not used 
* If an IDE is used, what extensions or plugins are enhancing security?
* How do you encouage automated security tests in local environments?
* The development environment should be secured
* What challenges does BYOD bring with it?

### How do I secure it?

* Use of git or other version control systems
* .gitignore files
* Endpoint detection and response (EDR)
* Linting
* Local secret scans
* Local SCA scans 
* Pre-commit git hooks

