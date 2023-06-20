# Visualizing the Software Supply Chain

The software supply chain is under increasing threat.  New attacks and threats have popped up that we couldn't have imagined even two years ago.  Total attacks on the software supply chain are increasing by more than [730% year on year since 2019](https://portswigger.net/daily-swig/researchers-find-633-increase-in-cyber-attacks-aimed-at-open-source-repositories)

Unfortunately, there is no consistent agreement on what is in the software supply chain. This is a problem as we can't secure the software supply chain if we don't know what's in it.  This project aims to help fix that by giving people a visual and contextual way to understand what specific components are in a particular software supply chain.  If you want to tag your own components you can fork this repo and edit it to suit your specific software supply chain profiles. 

![Visualizing the Software Supply Chain](/docs/images/Software-Supply-Chain-Visualization.png)

<center>

## The Software Supply Chain Stages

| [People](/docs/PEOPLE.md) | [Local Reqs](/docs/LOCAL.md) | [Source Code](/docs/CODE.md) | [Integration](/docs/INTEGRATION.md) | [Deployment](/docs/DEPLOYMENT.md) | [Runtime](/docs/RUNTIME.md) | [Hardware](/docs/HARDWARE.md) | [DNS](/docs/DNS.md)  | [Services](/docs/SERVICES.md) | [Cloud](/docs/CLOUD.md)
| :---------: | :----------: | :--------------: | :-----------: | :------------------: | :-----------------: | :---------: | :------: | :----------------: | :---------:
|             |              |                  |               |                      |                     |             |          |                    |                 |
| Developers  | IDE          | Languages        | Git repos     | Build solutions      | Servers             | Embedded PC | URL      | SaaS solutions     | CDN             |
| QA team     | SCV          | Frameworks       | SCM providers | Deployment platforms | Operating systems   | PCB         | hostname | Third party APIs   | Cloud services  |
| DevOps team | Local tests  | Libraries        | Pull requests | Unit tests           | Webservers          | USB dongle  |          | Payment gateways   |                 |
|             |              | Open source      |               | Functional tests     | Application servers | GPU/CPU     |          | Identity Providers |                 |
|             |              | Proprietary code |               | Security tests       | Web engines         |             |          | Analytics          |                 |
|             |              |                  |               |                      | Databases           |             |          |                    |                 |
| [People](/docs/PEOPLE.md) | [Local Reqs](/docs/LOCAL.md) | [Source Code](/docs/CODE.md) | [Integration](/docs/INTEGRATION.md) | [Deployment](/docs/DEPLOYMENT.md) | [Runtime](/docs/RUNTIME.md) | [Hardware](/docs/HARDWARE.md) | [DNS](/docs/DNS.md)  | [Services](/docs/SERVICES.md) | [Cloud](/docs/CLOUD.md)

</center>

## People

These are the individuals or teams of people that are needed to write, build and deploy software.

### What's in scope?

* Software engineers
* QA team
* DevOps team

### Examples

#### Developers

![collaborators-github](/docs/images/collaborators-github.png)

