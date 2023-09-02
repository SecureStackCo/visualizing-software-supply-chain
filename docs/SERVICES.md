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

### Who owns it?

* CloudOps team
* Marketing team

### How do I secure it?

* Centralized audit logs 
* Vendor key management
* Content security policy
* Just in time access control
