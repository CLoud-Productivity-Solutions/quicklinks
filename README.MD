# QuickLinks

## Summary

[Short summary on functionality and used technologies.]

[Picture of the solution in action, if possible]

## Used SharePoint Framework Version

![version](https://img.shields.io/badge/version-1.17.4-green.svg)

## Applies to

- [SharePoint Framework](https://aka.ms/spfx)
- [Microsoft 365 tenant](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/set-up-your-developer-tenant)

> Get your own free development tenant by subscribing to [Microsoft 365 developer program](http://aka.ms/o365devprogram)

## Prerequisites

[Any special pre-requisites?]

## Solution

| Solution    | Author(s)                                               |
| ----------- | ------------------------------------------------------- |
| folder name | Author details (name, company, twitter alias with link) |

## Version history

| Version | Date             | Comments        |
| ------- | ---------------- | --------------- |
| 1.1     | March 10, 2021   | Update comment  |
| 1.0     | January 29, 2021 | Initial release |

## Disclaimer

**THIS CODE IS PROVIDED _AS IS_ WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**

---

## Minimal Path to Awesome

- Install Node.js v16.20.2
- In the command-line run:
  - **npm install gulp-cli --global**
  - **npm install yo --global**
  - **npm install @microsoft/generator-sharepoint --global**

- Clone this repository
- Ensure that you are at the solution folder
- In the command-line run:
  - **npm install**
  - **gulp trust-dev-cert** to generate a certificate
   
- To make and preview changes:
  - **gulp serve**
  - To preview changes, copy the query string generated in the command-line and append it to https://ugandairlinesug.sharepoint.com to have a complete URL such as https://ugandairlinesug.sharepoint.com/?debug=true&noredir=true&debugManifestsFile=https://localhost:4321/temp/manifests.js

- To commit the changes:
  - **gulp package-solution --ship**
  - Upload the ./sharepoint/solution/quicklinks.sppkg to SharePoint admin
  - You should be able to view the changes in 6 to 12 hours

## Features

Description of the extension that expands upon the high-level summary above.

This extension illustrates the following concepts:

- Topic 1
- Topic 2
- Topic 3

> Notice that better pictures and documentation will increase the sample usage and the value you are providing for others. Thanks for your submissions in advance.

> Share your web part with others through Microsoft 365 Patterns and Practices program to get visibility and exposure. More details on the community, open-source projects, and other activities from [http://aka.ms/m365pnp](http://aka.ms/m365pnp).

## References

- [Getting started with SharePoint Framework](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/set-up-your-developer-tenant)
- [Building for Microsoft Teams](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/build-for-teams-overview)
- [Use Microsoft Graph in your solution](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/web-parts/get-started/using-microsoft-graph-apis)
- [Publish SharePoint Framework applications to the Marketplace](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/publish-to-marketplace-overview)
- [Microsoft 365 Patterns and Practices](https://aka.ms/m365pnp) - Guidance, tooling, samples, and open-source controls for your Microsoft 365 development