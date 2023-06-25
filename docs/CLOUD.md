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

<img src="images/firebase.svg" width="50" height="50" title="Firebase">  <img src="images/aws-api-gateway.svg" width="50" height="50" title="AWS API Gateway">  <img src="images/aws-cognito.svg" width="50" height="50" title="AWS Cognito">  <img src="images/aws-api-gateway.svg" width="50" height="50" title="AWS API Gateway">  

DynamoDB, Azure Functions, Microsoft Power Apps, Azure Cosmos, Azure Application Gateway, AWS Elastic Load Balancer, AWS Certificate Manager

### Who owns it?

* CloudOps team
* DevOps team

### What are the security concerns?

* Reference the shared responsibility model 
* Many of the cloud services are publicly facing endpoints by default
* What permissions are the cloud services using?
* How many assets do you have in the cloud?

### How do I secure it?

* Cloud Security Posture Mananagement
* Attack surface mapping
