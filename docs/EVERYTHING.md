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

## People

These are the individuals or teams of people that are needed to write, build and deploy software.

### What's in scope?

* Software engineers
* QA team
* DevOps team

### Examples

#### Developers

![collaborators-github](images/collaborators-github.png)

&nbsp;&nbsp;

## Local Requirements 

This includes any local applications, configurations, or other dependencies that are needed to for the people building software to successfully do their job.

### What's in scope?

* IDE
* VCS tools
* Local tests

### Examples

#### IDE

<img src="images/vscode.png" width="50" height="50" title="VS Code">  <img src="images/atom.png" width="50" height="50" title="Atom">  <img src="images/vim.png" width="50" height="50" title="Vim">

#### VCS Tools

<img src="images/git.svg" width="50" height="50" title="Git">  <img src="images/mercurial.png" width="50" height="50" title="Mercurial">  <img src="images/clearcase.png" width="50" height="50" title="Clearcase">

#### Local tests

Linting, static analysis, software composition analysis

&nbsp;&nbsp;

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

## Continuous Integration

Continuous integration (CI) is the process of automatically integrating code changes from multiple contributors into a single software project. This is an important DevOps best practice that enables developers to frequently merge code changes into a central repository for testing before deployment. Automated tools are used to check that the new code is correct before integration.

### What's in scope?

* SCM providers
* Pull requests

### Examples

#### SCM Providers

<img src="images/github.svg" width="50" height="50" title="GitHub">  <img src="images/bitbucket.svg" width="50" height="50" title="Bitbucket">  <img src="images/azure-repos.png" width="50" height="50" title="Azure Repos"> <img src="images/gitlab.svg" width="50" height="50" title="GitLab">  <img src="images/gitea.png" width="50" height="50" title="Gitea">  <img src="images/codecommit.png" width="50" height="50" title="CodeCommit">

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

&nbsp;&nbsp;

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

&nbsp;&nbsp;

## Hardware

This includes any specific or customized piece of hardware for this application to run.  

### What's in scope?

* Proprietary devices
* Dedicated servers

### Examples

Embedded devices, custom PCBs, GPUs

&nbsp;&nbsp;

## DNS

This includes any hostnames, or other DNS entries that any application needs.

### What's in scope?

* DNS

### Examples

app.example.org

&nbsp;&nbsp;

## Services

This refers to the process of identifying and describing the external services that a application relies on in order to function properly. These third-party services can include anything from authentication and authorization services to payment processing and analytics tools.

### What's in scope?

* third party SaaS solutions
* third party APIs or data
* payment processors/gateways
* identity providers 
* analytics & tracking

### Examples

#### Payment gateways & processors

<img src="images/paypal.svg" width="50" height="50" title="Paypal">  <img src="images/stripe.svg" width="50" height="50" title="Stripe">  <img src="images/braintree.png" width="75" height="50" title="Braintree">  <img src="images/square.jpeg" width="50" height="50" title="Square">

#### SaaS solutions examples

<img src="images/hubspot.svg" width="50" height="50" title="Hubspot">  <img src="images/mailchimp.svg" width="50" height="50" title="Mailchimp">  <img src="images/linkedin.svg" width="50" height="50" title="LinkedIn">  <img src="images/crunchbase.png" width="50" height="50" title="Crunchbase">

#### Analytics & tracking examples

<img src="images/google-analytics.svg" width="50" height="50" title="Google Analytics">  <img src="images/hotjar.svg" width="50" height="50" title="Hotjar">  <img src="images/facebook.svg" width="50" height="50" title="Facebook Pixel">  <img src="images/segment.svg" width="50" height="50" title="Segment"> <img src="images/marketo.svg" width="50" height="50" title="Marketo"> <img src="images/mixpanel.png" width="75" height="50" title="Mixpanel">

&nbsp;&nbsp;

## Cloud resources

Cloud native resources refer to the tools, technologies, and infrastructure required to develop, deploy, and manage applications that are designed to run in a cloud environment. These resources typically include containerization platforms, orchestration frameworks, serverless computing, and other cloud-specific technologies.

### What's in scope?

* PaaS
* CDN
* Cloud hosting providers
* Cloud native resources

### Examples

#### PaaS Examples

<img src="images/vercel.svg" width="50" height="50" title="Vercel">  <img src="images/kinsta.svg" width="50" height="50" title="Kinsta">  <img src="images/flywheel.svg" width="50" height="50" title="Flywheel">

#### CDN Examples

<img src="images/cloudfront.svg" width="50" height="50" title="Cloudfront">  <img src="images/cloudflare.svg" width="50" height="50" title="Cloudflare">  <img src="images/fastly.svg" width="50" height="50" title="Fastly">  <img src="images/peakhour.png" width="50" height="50" title="Peakhour">  <img src="images/akamai.svg" width="50" height="50" title="Akamai">

#### Cloud hosting providers

<img src="images/aws.svg" width="50" height="50" title="AWS">  <img src="images/azure.svg" width="50" height="50" title="Azure">  <img src="images/google-cloud.svg" width="50" height="50" title="Google Cloud">  <img src="images/alibaba-cloud.png" width="50" height="50" title="Alibaba">

#### Cloud Native Services

<img src="images/firebase.svg" width="50" height="50" title="Firebase">  <img src="images/aws-api-gateway.svg" width="50" height="50" title="AWS API Gateway">  <img src="images/aws-cognito.svg" width="50" height="50" title="AWS Cognito">  <img src="images/.svg" width="50" height="50" title="Firebase">  <img src="images/aws-api-gateway.svg" width="50" height="50" title="AWS API Gateway">  

DynamoDB, Azure Functions, Microsoft Power Apps, Azure Cosmos, Azure Application Gateway, AWS Elastic Load Balancer, AWS Certificate Manager
