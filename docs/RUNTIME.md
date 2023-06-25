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

### How do I secure it?

* 
