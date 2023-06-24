<center>

## The Software Supply Chain Stages

| [People](docs/PEOPLE.md) | [Local Reqs](docs/LOCAL.md) | [Source Code](docs/CODE.md) | [Integration](docs/INTEGRATION.md) | [Deployment](docs/DEPLOYMENT.md) | [Runtime](docs/RUNTIME.md) | [Hardware](docs/HARDWARE.md) | [DNS](docs/DNS.md)  | [Services](docs/SERVICES.md) | [Cloud](docs/CLOUD.md)
| :---------: | :----------: | :--------------: | :-----------: | :------------------: | :-----------------: | :---------: | :------: | :----------------: | :---------:
|             |              |                  |               |                      |                     |             |          |                    |                 |
| Developers  | IDE          | Languages        | SCM providers | Build solutions      | Servers             | Embedded PC | URL      | SaaS solutions     | CDN             |
| QA team     | SCV          | Frameworks       | Pull requests | Deployment platforms | Operating systems   | PCB         | hostname | Third party APIs   | Cloud services  |
| DevOps team | Local tests  | Libraries        | Secrets mgmt  | Unit tests           | Webservers          | USB dongle  |          | Payment gateways   |                 |
|             | Git repos    | Package Managers |               | Functional tests     | Application servers | GPU/CPU     |          | Identity Providers |                 |
|             |              | Proprietary code |               | Security tests       | Web engines         |             |          | Analytics          |                 |
|             |              | Open source      |               | API test frameworks  | Databases           |             |          |                    |                 |
| [People](docs/PEOPLE.md) | [Local Reqs](docs/LOCAL.md) | [Source Code](docs/CODE.md) | [Integration](docs/INTEGRATION.md) | [Deployment](docs/DEPLOYMENT.md) | [Runtime](docs/RUNTIME.md) | [Hardware](docs/HARDWARE.md) | [DNS](docs/DNS.md)  | [Services](docs/SERVICES.md) | [Cloud](docs/CLOUD.md)

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

