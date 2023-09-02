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

## Source Code

This includes any software that is needed to successfully write, build or deploy an application.  

### What's in scope?

* Programming languages
* Frameworks
* Libraries
* Package managers
* Open source components
* Proprietary code

### Examples

#### Programming Languages

<img src="images/javascript.svg" width="50" height="50" title="Javascript">  <img src="images/python.svg" width="50" height="50" title="Python">  <img src="images/ruby.svg" width="50" height="50" title="Ruby">  <img src="images/java.svg" width="50" height="50" title="Java">  <img src="images/php.svg" width="50" height="50" title="PHP">  <img src="images/go.svg" width="50" height="50" title="Go">  <img src="images/cplusplus.png" width="50" height="50" title="C++">  <img src="images/csharp.png" width="50" height="50" title="C#">  <img src="images/rust.svg" width="50" height="50" title="Rust">

#### Frameworks & libraries

<img src="images/react.svg" width="50" height="50" title="React">  <img src="images/django.svg" width="50" height="50" title="Django">  <img src="images/next-js.svg" width="50" height="50" title="Next.js">  <img src="images/jquery.svg" width="50" height="50" title="Jquery">  <img src="images/angular.svg" width="50" height="50" title="Angular.js">  <img src="images/vue.svg" width="50" height="50" title="Vue.js">  <img src="images/laravel.svg" width="50" height="50" title="Laravel">  <img src="images/nuxt-js.svg" width="50" height="50" title="Nuxt.js">  <img src="images/moment-js.svg" width="50" height="50" title="Moment.js">  <img src="images/babel.svg" width="50" height="50" title="Babel.js">  <img src="images/lodash.svg" width="50" height="50" title="Lodash">  <img src="images/swiper.svg" width="50" height="50" title="Swiper">  <img src="images/tailwind.svg" width="50" height="50" title="Tailwind CSS">  <img src="images/netcore.svg" width="50" height="50" title=".NET Core">  <img src="images/require-js.svg" width="50" height="50" title="Require.js">  <img src="images/fastapi.svg" width="50" height="50" title="FastAPI">

#### Package managers

<img src="images/maven.svg" width="100" height="30" title="Maven">  <img src="images/pypi.png" width="80" height="40" title="PyPi">  <img src="images/npm.png" width="80" height="30" title="NPM">  <img src="images/nuget.png" width="50" height="50" title="Nuget">  <img src="images/yarn.png" width="50" height="50" title="Yarn">  <img src="images/composer.png" width="50" height="50" title="Composer">  <img src="images/packagist.png" width="50" height="50" title="Packagist">

### Who owns it?

* Development teams
* DevOps team

### What are the security concerns?

* Knowing what's in your software is the first key
* Source code components are coming from many different sources and used in applications
* Dependency origin for the source code we use is critically important
* Package managers are a primary target for attackers

### How do I secure it?

* Use secure package repositories
* Analysis source code composition
* Software bill of materials
