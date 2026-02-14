# Webflow API & MCP Sandbox
This is an API sandbox for the Webflow API & MCP Sandbox, using an OpenAPI specification with examples, Microcks and Bruno as the sandbox interface, and this GitHub repository as the vehicle for delivering a localized sandbox.

## APIs.json
There is an APIs.yml file in the root of this repository, providing an index of all the artifacts used as part of this API sandbox, providing a machine-readable way to read, manage, and execute the sandbox available here.

## OpenAPI
This sandbox uses OpenAPI as the definition, providing [a complete definition of all available paths for the Webflow API & MCP Sandbox. The OpenAPI for this sandnbox uses examples and Microcks extensions to mock the requests and responses for each API operation, something we will iterate and expand upon with richer examples as we move forward.

## Microcks
This sandbox uses Microcks to deliver the mock API. [You just install Microcks, with the Docker extension being the easiest](https://microcks.io/documentation/guides/installation/docker-desktop-extension/), [import the OpenAPI as a service](openapi/notion-openapi.yml), and you have a mocked API for all APIs, available via REST and MCP APIs--providing a multi-protocol sandbox.

## Bruno
This sandbox [uses Bruno as the client](https://www.usebruno.com/), leveraging Bruno Collections pre-generated from the OpenAPI and Bruno environments that uses the localhost and port of Microcks to work with the mocked API. You just have to install Microcks, then open the collection provided in this repository, select the available environment, and begin calling the Webflow API & MCP Sandbox via the sandbox.

## Summary
This is a summary of this sandbox, breaking down the available paths, operations, and other relevant detail regarding the scope of this sandbox, designed to support development and testing against the Webflow API & MCP Sandbox.

- Number of Paths: 77
- Number of Operations: 128
- Number of Read Operations: 60
- Number of Write Operations: 68
- Number of Schemas: 970
- Number of Responses: 5
- Number of Parameters: 27
- Number of Examples: 996
- Number of Request Bodies: 0
- Number of Headers: 0

## OpenAPIs
These are the OpenAPIs available for the Webflow API & MCP Sandbox, which are made available via this sandbox API, which can be imported into Microcks and deployed as a sandbox using their mock feature.

  - [Webflow Asset Folders Api](openapi/asset-folders-openapi-original.yml)
  - [Webflow Assets Api](openapi/assets-openapi-original.yml)
  - [Webflow Collections Api](openapi/collections-openapi-original.yml)
  - [Webflow Form Submissions Api](openapi/form-submissions-openapi-original.yml)
  - [Webflow Forms Api](openapi/forms-openapi-original.yml)
  - [Webflow Pages Api](openapi/pages-openapi-original.yml)
  - [Webflow Sites Api](openapi/sites-openapi-original.yml)
  - [Webflow Token Api](openapi/token-openapi-original.yml)
  - [Webflow Webhooks Api](openapi/webhooks-openapi-original.yml)
  - [Webflow Workspaces Api](openapi/workspaces-openapi-original.yml)

## Resources
These are the resources available via the Webflow API & MCP Sandbox, which are made available via this sandbox API, which are applied as tags to each operation in the OpenAPI.

  - Access Groups
  - Activity Logs
  - Asset Folders
  - Assets
  - Audit Logs
  - Authorization
  - Bulk Operations
  - Collection Fields
  - Collection Items
  - Collections
  - Comments
  - Components
  - Custom Code
  - Custom Domains
  - Ecommerce Settings
  - Form Details
  - Form Submissions
  - Forms
  - Inventory Management
  - Live Collection Items
  - Orders
  - Page Content
  - Page Custom Code
  - Page Metadata
  - Pages
  - Products
  - Publishing
  - Redirects
  - Robots Configuration
  - Scripts
  - Site Form Submissions
  - Site Forms
  - Site Pages
  - Site Plans
  - Site Publishing
  - Sites
  - Skus
  - Token Management
  - Users
  - Webhooks
  - Well Known

## Operations
These are all of the available operations in this sandbox, providing a complete view of what you can do within this sandbox using the mocked Webflow API & MCP Sandbox.

  - Add Or Update Page Custom Code
  - Add/update Custom Code
  - Create Asset Folder
  - Create Asset Folder
  - Create Collection
  - Create Collection
  - Create Collection Field
  - Create Collection Item
  - Create Live Collection Item
  - Create Multiple Collection Items
  - Create Product & Sku
  - Create Skus
  - Create Site
  - Create Site
  - Create Webhook
  - Create Webhook
  - Create A 301 Redirect
  - Create And Invite A User
  - Delete 301 Redirects
  - Delete Asset
  - Delete Collection
  - Delete Collection Field
  - Delete Collection Item
  - Delete Custom Code
  - Delete Form Submission
  - Delete Form Submission By Site
  - Delete Form Submission By Site
  - Delete Live Collection Item
  - Delete Multiple Collection Items
  - Delete Multiple Live Collection Items
  - Delete Page Custom Code
  - Delete Site
  - Delete User
  - Delete A Well-known File
  - Delete Robots.txt
  - Fulfill Order
  - Get 301 Redirects
  - Get Asset
  - Get Asset Folder
  - Get Authorization Info
  - Get Authorization User Info
  - Get Collection Details
  - Get Collection Item
  - Get Comment Thread
  - Get Component Content
  - Get Component Properties
  - Get Custom Code
  - Get Custom Domains
  - Get Ecommerce Settings
  - Get Form Schema
  - Get Form Submission
  - Get Form Submission By Site
  - Get Form Submission By Site
  - Get Live Collection Item
  - Get Order
  - Get Page Content
  - Get Page Custom Code
  - Get Page Metadata
  - Get Product And Skus
  - Get Registered Scripts
  - Get Site
  - Get Site Activity Logs
  - Get Site Plan
  - Get User
  - Get Webhook
  - Get Workspace Audit Logs
  - Get Robots.txt
  - List Access Groups
  - List Asset Folders
  - List Asset Folders
  - List Assets
  - List Assets
  - List Collection Items
  - List Collections
  - List Collections
  - List Comment Replies
  - List Comment Threads
  - List Components
  - List Custom Code Blocks
  - List Form Submissions
  - List Form Submissions
  - List Form Submissions By Site
  - List Form Submissions By Site
  - List Forms
  - List Inventory
  - List Live Collection Items
  - List Orders
  - List Pages
  - List Products & Skus
  - List Site Form Submissions
  - List Site Forms
  - List Site Pages
  - List Sites
  - List Users
  - List Webhooks
  - List Webhooks
  - Modify Form Submission By Site
  - Publish Collection Items
  - Publish Site
  - Refund Order
  - Register Script - Hosted
  - Register Script - Inline
  - Remove Webhook
  - Replace Robots.txt
  - Set A Well-known File
  - Unfulfill Order
  - Update 301 Redirect
  - Update Asset
  - Update Collection Field
  - Update Collection Item
  - Update Component Content
  - Update Component Properties
  - Update Form Submission
  - Update Form Submission By Site
  - Update Inventory
  - Update Live Collection Item
  - Update Multiple Collection Items
  - Update Multiple Live Collection Items
  - Update Order
  - Update Page Content
  - Update Page Metadata
  - Update Product
  - Update Sku
  - Update Site
  - Update User
  - Update Robots.txt
  - Upload Asset
  - Upload Asset

## Backstage
We provide a Backstage software catalog entity for the Webflow API & MCP Sandbox, allowing this sandbox to be registered with any catalog, making it discoverable by team and across an organization--allowing anyone to fork and deploy locally within the enterprise.

  - [Webflow Asset Folders API](backstage/asset-folders-backstage-original.yml)
  - [Webflow Assets API](backstage/assets-backstage-original.yml)
  - [Webflow Collections API](backstage/collections-backstage-original.yml)
  - [Webflow Form Submissions API](backstage/form-submissions-backstage-original.yml)
  - [Webflow Forms API](backstage/forms-backstage-original.yml)
  - [Webflow Pages API](backstage/pages-backstage-original.yml)
  - [Webflow Sites API](backstage/sites-backstage-original.yml)
  - [Webflow Token API](backstage/token-backstage-original.yml)
  - [Webflow Webhooks API](backstage/webhooks-backstage-original.yml)
  - [Webflow Workspaces API](backstage/workspaces-backstage-original.yml)
## Support
Please provide any questions or feedback via GitHub issues, or just email kinlane@naftiko.io with feedback. The goal is to keep iterating upon this sandbox using existing OpenAPI, Microcks, and Bruno features, offering value out of the box via this forkable third-party Webflow API & MCP Sandbox.

