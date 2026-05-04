# Blueprint4D 2026 ASF Demo Project

This repository contains the Application Designer project for the ASF demo project. There are no changes to any delivered objects. Copy the BP4D_DEMO folder to a location accessible to your Application Designer client and import it from that location. There is nothing to build.

You must be on PeopleTools 8.59 at a minimum.

Also included is the OpenAPI version of the API (`BP4D_DEMO.openapi.json`). This can be loaded into Apidog or any other OpenAPI-compatible tool to test with your installation. You will need to supply your local host path. You can find this at PeopleTools > Integration Broker > Service Configuration | Service Configuration: Setup Target Locations. It should be something like `https://example.com/PSIGW/RESTListeningConnector/PSFT`. Append /bp4d.v1 and you will have the base URL for the defined root resources.

## Remember

Whichever account you wish to experiment with, ensure that one of the permissions lists assigned to that account is applied to all the endpoints. I recommend basic authentication for your testing. This site can generate the value for you: <https://www.debugbear.com/basic-auth-header-generator>

## OpenAPI Specification
You can view the OpenAPI specification here: <https://ftdav67csd.apidog.io/>. The password is KDeDfPKC.
