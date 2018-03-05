# Luke Abbott
NetSuite administrator, SuiteScript developer, JavaScript and React enthusiast.
## Technology Stack
* SuiteScript
* SuiteFlow
* Dell Boomi Atomsphere
* SuiteCommerce
* NodeJS
* Amazon Web Services
* WebPack
## Projects
Over the last I have worked on a multitude of projects that cover business logic implementations, ecommerce feature additions, EDI integrations, and more.
### Work Tracking Module
A mortgage originator needed a method to track which agent was working on a mortgage opportunity and what the state of that opportunity was. I built an integration between their mortgage origination software and their NetSuite account to provide a single source of truth for their metrics.
### JSON Faceted Search
I designed a JSON file based faceted search for an ecommerce site. The site needed a faster search experience so I utilised NetSuite's scheduled scripting functionality to cache item data in JSON files. These files were then used to generate category specific faceted search.
### Freight Shipment Tracking
Freight carriers were providing csv files with shipment statuses on a nightly basis. The files needed to be translated into a NetSuite compatible format before import. The import needed to not overwrite previously imported freight data. The process realied on an excel macro that needed to be manually updated for each freight carrier.

I converted the excel macro process into a NodeJS application that allowed the user to configure the CSV conversion as needed. The application then connected to a custom NetSuite restlet that handled data validation and importing.