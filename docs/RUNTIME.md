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

## Runtime

The web application runtime is the environment in which a web application is executed. It typically includes the web server, the application server, and other necessary components such as databases, messaging systems, and caching mechanisms. The runtime is responsible for managing the application's resources, handling incoming requests, and returning responses to users.

### What's in scope

* Operating systems
* Webservers
* Application servers
* Content management systems
* Web runtime engines
* Databases
* Containers, AMIs & golden images

### Examples

#### Operating systems

<img src="images/linux.svg" width="50" height="50" title="Linux">  <img src="images/windows-server.svg" width="50" height="50" title="Windows Server">  <img src="images/freebsd.png" width="50" height="50" title="FreeBSD"> <img src="images/unix.svg" width="50" height="50" title="Unix">  <img src="images/ubuntu.svg" width="50" height="50" title="Ubuntu">  <img src="images/redhat.svg" width="50" height="50" title="RedHat">

#### Webservers

<img src="images/apache.svg" width="50" height="50" title="Apache">  <img src="images/nginx.svg" width="50" height="50" title="Nginx">  <img src="images/microsoft-iis-logo.png" width="50" height="50" title="Microsoft IIS">  <img src="images/express.svg" width="50" height="50" title="Express">

#### Application servers

<img src="images/tomcat.svg" width="50" height="50" title="Apache Tomcat">  <img src="images/websphere.png" width="50" height="50" title="WebSphere">  <img src="images/glassfish.png" width="50" height="50" title="GlassFish">  <img src="images/aspnet.png" width="50" height="50" title="ASP.NET">

#### Content management systems

<img src="images/wordpress.svg" width="50" height="50" title="WordPress">  <img src="images/drupal.svg" width="50" height="50" title="Drupal">  <img src="images/joomla.png" width="50" height="50" title="Joomla">  <img src="images/contentful.svg" width="50" height="50" title="Contentful">  <img src="images/magento.svg" width="50" height="50" title="Magento">

Clarity, Kentico, Sharepoint, Adobe Experience Manager

#### Web runtime

Node.js, WebKit, Chrome, V8 

#### Databases

<img src="images/mysql.svg" width="50" height="50" title="MySQL">  <img src="images/postgres.svg" width="50" height="50" title="Postgres">  <img src="images/redis.svg" width="50" height="50" title="Redis">  <img src="images/microsoft-sql-server-logo.svg" width="50" height="50" title="SQL Server">

#### Containers, AMIs & Golden Images

<img src="images/docker.png" width="50" height="50" title="Docker">  <img src="images/kubernetes.svg" width="50" height="50" title="Kubernetes">  <img src="images/amazon-linux-logo.png" width="50" height="50" title="Amazon Linux">

### Who owns it?

* CloudOps team
* Operations teams

### Security concerns with runtime components?

* Traditional concerns around server security: patching, firewalls, user access, etc
* Container origin is a huge concern as Docker hub and container registries are prime areas for dependency attacks
* Runtime components have multiple layers of user access controls to worry about
* Golden images and AMIs don't age well, and are often "pinned" in launch 

### How do I secure it?

* Centralized logging
* SIEM
* Intrusion detection/prevention
* OS hardening 
* Web appliation firewall
* Container scanning
* IaC scans
