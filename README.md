# Inmarsat IsatData Pro Developer Kit Quick Start

<img alt="Developer Kit" src="./docs/media/kit-open-box.png" width="75%" height="auto">

The IDP Developer Kit comes with everything you need to start working with
Inmarsat's Non-IP IoT messaging service ***IsatData Pro***:
    
* A satellite modem, self-contained with antenna and GPS/GNSS in a weatherproof
enclosure
* Cables to connect to AC or vehicle DC power, including an international power
adapter, cable extenders and a magnetic roof-mount for the satellite modem
* A single-board computer (SBC) with interface to the satellite modem, which
provides:
    * WiFi link between a laptop, tablet or smartphone and the satellite modem
    * A Graphical User Interface to the satellite modem and SBC
    * A simple demo "Edge" application that generates location and modem
    telemetry data and allows sending/receiving text messages

## Before you begin...

>:information_source: Inmarsat provides the Developer Kit to qualified
[***ELEVATE***](https://www.inmarsat.com/en/solutions-services/enterprise/services/elevate.html)
partners.

1. You will need a [GitHub](https://github.com) account. Create one for free if
you do not already have one, and send it to your Inmarsat *Elevate* point of
contact. We will set you up with *collaborator* access to our private
repositories.

2. You should have received the **IDP Developer Kit Welcome Email** from
Inmarsat:

    <img alt="ASP Welcome Email" src="./docs/media/ASP Welcome Email.jpg"
    width="75%" height="auto">

3. You should also have received login instructions for the
[Inmarsat Solutions IDP Portal](https://isipinmarsat.satcomhost.com).

> If you have not received your welcome email and ISIP login instructions
please contact enterprisesales@inmarsat.com

## Getting Started

We recommend you read the full contents, but if you want to jump-start go
straight to [Modem Activation](docs/modem-activation.md) then
[Kit Installation](docs/kit-installation.md) then
[Network Data](docs/Network-Data.md)

* [System Overview](docs/system-overview.md)
* [Modem Activation](docs/modem-activation.md)
* [Kit Installation](docs/kit-installation.md)
* [Network Data](docs/network-data.md)
* [Using the Demo Application](docs/demo-application.md)
* [Next Steps](#Next-Steps)

## Next Steps

Ensure you have access to the following documentation: (right click links to open in a new tab)

1. [**Modem Integration Documentation**](https://github.com/inmarsat-enterprise/idp-developer-kit-nda)
on Inmarsat Enterprise private GitHub repository.
    
1. [**IDP Messaging API**](https://developer.inmarsat.com/technology/idp/idp-messaging-api/idp-messaging-api/)
on the Inmarsat Developer Portal.

1. [**Inmarsat FieldEdge Project**](https://github.com/orgs/inmarsat-enterprise/projects/1)
with links to the sub-project repositories (see *Details*).

Inmarsat also provides the following open source reference material:

* [**idpmodem**](https://github.com/inmarsat/idpmodem)
Python 3.x package on PyPI and GitHub interfacing the modem using AT commands.

* [**isatdatapro-api**](https://www.npmjs.com/package/isatdatapro-api)
Node.js package on NPM interfacing a web client to the network API.

* [**Azure IoT Satellite Messaging Reference Architecture**](https://github.com/Inmarsat/isatdatapro-azure)
on GitHub.

[Back to Top](#Inmarsat-IsatData-Pro-Plug-N-Play-Developer-Kit-Quick-Start)

