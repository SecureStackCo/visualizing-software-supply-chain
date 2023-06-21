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

## Source Code

This includes any software that is needed to successfully write, build or deploy an application.  

### What's in scope?

* Programming languages
* Frameworks
* Libraries
* Open source components
* Proprietary code

### Examples

#### Programming Languages

<img src="images/javascript.svg" width="50" height="50" title="Javascript">  <img src="images/python.svg" width="50" height="50" title="Python">  <img src="images/ruby.svg" width="50" height="50" title="Ruby">  <img src="images/java.svg" width="50" height="50" title="Java">  <img src="images/php.svg" width="50" height="50" title="PHP">  <img src="images/go.svg" width="50" height="50" title="Go">  <img src="images/cplusplus.png" width="50" height="50" title="C++">  <img src="images/csharp.png" width="50" height="50" title="C#">  <img src="images/rust.svg" width="50" height="50" title="Rust">

#### Frameworks & libraries

<img src="images/react.svg" width="50" height="50" title="React">  <img src="images/django.svg" width="50" height="50" title="Djange">  <img src="images/next-js.svg" width="50" height="50" title="Next.js">  <img src="images/jquery.svg" width="50" height="50" title="Jquery">  <img src="images/angular.svg" width="50" height="50" title="Angular.js">  <img src="images/vue.svg" width="50" height="50" title="Vue.js">  <img src="images/laravel.svg" width="50" height="50" title="Laravel">  <img src="images/nuxt-js.svg" width="50" height="50" title="Nuxt.js">  <img src="images/moment-js.svg" width="50" height="50" title="Moment.js">  <img src="images/babel.svg" width="50" height="50" title="Babel.js">  <img src="images/lodash.svg" width="50" height="50" title="Lodash">  <img src="images/swiper.svg" width="50" height="50" title="Swiper">  <img src="images/tailwind.svg" width="50" height="50" title="Tailwind CSS">  <img src="images/netcore.svg" width="50" height="50" title=".NET Core">  <img src="images/require-js.svg" width="50" height="50" title="Require.js">  <img src="images/fastapi.svg" width="50" height="50" title="FastAPI">

