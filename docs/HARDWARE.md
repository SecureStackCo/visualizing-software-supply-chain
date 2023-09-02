<center>

## The Software Supply Chain Stages

| [People](docs/PEOPLE.md#people) | [Local Reqs](docs/LOCAL.md#local-requirements) | [Source Code](docs/CODE.md#source-code) | [Integration](docs/INTEGRATION.md#continuous-integration) | [Deployment](docs/DEPLOYMENT.md#continuous-deployment) | [Runtime](docs/RUNTIME.md#runtime) | [Hardware](docs/HARDWARE.md#hardware) | [DNS](docs/DNS.md#dns)  | [Services](docs/SERVICES.md#services) | [Cloud](docs/CLOUD.md#cloud-resources)
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
| [People](docs/PEOPLE.md#people) | [Local Reqs](docs/LOCAL.md#local-requirements) | [Source Code](docs/CODE.md#source-code) | [Integration](docs/INTEGRATION.md#continuous-integration) | [Deployment](docs/DEPLOYMENT.md#continuous-deployment) | [Runtime](docs/RUNTIME.md#runtime) | [Hardware](docs/HARDWARE.md#hardware) | [DNS](docs/DNS.md#dns)  | [Services](docs/SERVICES.md#services) | [Cloud](docs/CLOUD.md#cloud-resources)

</center>

## Hardware

This includes any specific or customized piece of hardware for this application to run.  

### What's in scope?

* Proprietary devices
* Dedicated servers

### Examples

Embedded devices, custom PCBs, GPUs

### Who owns it?

* Operations team
* Cloud provider

### What are the security concerns?

* Hardware devices come with embedded software that is attack vector
* 

### How do I secure it?

* Buy from known supplier 
* Network analysis so you can detect malicious "phone home"
