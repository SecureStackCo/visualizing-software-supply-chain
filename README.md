# Visualizing the Software Supply Chain

The software supply chain is under increasing threat.  New attacks and threats have popped up that we couldn't have imagined even two years ago.  Total attacks on the software supply chain are increasing by more than [730% year on year since 2019](https://portswigger.net/daily-swig/researchers-find-633-increase-in-cyber-attacks-aimed-at-open-source-repositories)

Unfortunately, there is no consistent agreement on what is in the software supply chain.  This project aims to help fix that by giving people a visual and contextual way to understand what specific components are in a particular software supply chain.  

| People | Local Requirements | Source Code | Integration | Deployment | Runtime | Hardware | DNS | Services | Cloud
| :--- | :---        | :---   | :--- | :---    | :--- | :--- | :---        | :---   | :---
| Developers | IDE | Languages | Git repos | Build solutions | Servers | Embedded Device | DNS | SaaS solutions | AWS Cognito |
| QA team | VCS | Frameworks | SCM providers | Deployment platforms | Operating systems | PCB | | 3rd party APIs | API Gateway |
| DevOps team | Local tests | Libraries | Pull requests | Unit tests | Webservers | USB dongle |  | Payment gateways | |
| | | Open source | | Functional tests | Application servers | |  | Identity Providers | |
| | | Proprietary code | | Security tests | Web engines | |  | | |
| | | | | | Databases | | | | |

| People      | Local Requirements | Source Code   | Integration   | Deployment       | Runtime     | Hardware | DNS | Services | Cloud
| :---        | :---               | :---          | :---          | :---             | :---        | :---     | :---        | :---   | :---
| Developers  | IDE                | Languages     | Git repos     | Build solutions  | Servers     | Embedded Device | DNS | SaaS solutions | AWS Cognito |
| QA team     | VCS                | Frameworks    | SCM providers | Deployment platforms | Operating systems  | PCB | | 3rd party APIs | API Gateway |
| DevOps team | Local tests        | Libraries     | Pull requests | Unit tests       | Webservers  | USB dongle |  | Payment gateways | |
|             |                    | Open source   |               | Functional tests | Application servers | |  | Identity Providers | |
|             |                    | Proprietary code |            | Security tests   | Web engines | |  | | |
|             |                    |                  |            |                  | Databases   | |  | | |

## 1. People

These are the individuals or teams of people that are needed to write, build and deploy software.

### What's in scope?

* Software engineers
* QA team
* DevOps team

### Examples

peter.small@cheapcryptobank.com, roger.moore@cheapcryptobank.com

## 2. Local Environments

This includes any local applications, configurations, or other dependencies that are needed to for the people building software to successfully do their job.

### What's in scope?

* IDE
* SCV tools
* Local tests

### Examples

VSCode, Atom, Git, Vim, SVN, Mercurial, static analysis, software composition analysis

## 3. Source Code

This includes any software that is needed to successfully write, build or deploy an application.  

### What's in scope?

* Programming languages
* Frameworks
* Libraries
* Open source components
* Proprietary code

### Examples

Javascript, Python, C, C++, Ruby, C#, Java, Ruby on Rails, React, PHP, Django, Next.js, JQuery, Golang, Angular, Vue.js, Laravel, jsDelivr, Nuxt.js, Knockout.js, Underscore.js, Moment.js, Babel.js, Lodash, Swiper.js, Tailwind CSS, Lua, .NET Core, Require.js, Slick 

## 4. Source Code Management/Continuous Integration

Continuous integration (CI) is the process of automatically integrating code changes from multiple contributors into a single software project. This is an important DevOps best practice that enables developers to frequently merge code changes into a central repository for testing before deployment. Automated tools are used to check that the new code is correct before integration.

### What's in scope?

* Git repositories
* SCM providers
* Pull requests

### Examples

GitHub, Bitbucket, GitLab, CodeCommit, Azure Repos, Gitea 

## 5. Continuous deployment/delivery

Continuous delivery is an extension of continuous integration that automatically deploys all code changes to a testing and/or production environment after the build stage. This means that in addition to automated testing, you have an automated release process, and can deploy your application at any time by clicking a button.

### What's in scope?

* Build servers
* Deployment platforms
* Security tests
* Functional tests

### Examples

Buildkite, Bamboo, Octopus Deploy, Jenkins, Azure DevOps, Selenium, Semgrep, SecureStack

## 6. Runtime

The web application runtime is the environment in which a web application is executed. It typically includes the web server, the application server, and other necessary components such as databases, messaging systems, and caching mechanisms. The runtime is responsible for managing the application's resources, handling incoming requests, and returning responses to users.

### What's in scope

* Servers
* Operating systems
* Containers
* Webservers
* Application servers
* Web runtime engines
* Databases

### Examples

IIS, Express, Apache, Tomcat, ASP.NET, Node.js, WebKit, Chrome, V8, MySQL, PostGres, WordPress, WooCommerce, Kubernetes, Docker, Adobe Experience Manager, Vercel, Kinsta, Flywheel, Nginx, Linux, Ubuntu, CentOS, Amazon Linux 2, Drupal, Windows Server 

## 7. Hardware

This includes any specific or customized piece of hardware for this application to run.  

### What's in scope?

* Proprietary devices
* Dedicated servers

### Examples

Embedded devices, custom PCBs, GPUs

## 8. DNS

This includes any hostnames, or other DNS entries that any application needs.

### What's in scope?

* DNS

### Examples

app.example.org

## 9. Services

This refers to the process of identifying and describing the external services that a application relies on in order to function properly. These third-party services can include anything from authentication and authorization services to payment processing and analytics tools.

### What's in scope?

* third party SaaS solutions
* third party APIs or data
* payment processors/gateways
* identity providers 

### Examples

Stripe, Segment, Hubspot, Mailchimp, Facebook Pixel, Marketo

## 10. Cloud resources

Cloud native resources refer to the tools, technologies, and infrastructure required to develop, deploy, and manage applications that are designed to run in a cloud environment. These resources typically include containerization platforms, orchestration frameworks, serverless computing, and other cloud-specific technologies.

### What's in scope?

* CDN
* Cloud native resources

### Examples

AWS API Gateway, AWS Cognito, DynamoDB
