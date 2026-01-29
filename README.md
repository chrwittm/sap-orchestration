# SAP Orchestration Service Examples

Examples and tutorials for working with SAP's Orchestration Service using the Generative AI Hub SDK on AI Core.

## Tutorials

- [Hello World](./hello-world/hello-world.ipynb): Getting started with the Harmonized API - swap models with a single string change

## Setup

1. Install the SAP Cloud SDK for AI:

```bash
pip install "sap-ai-sdk-gen[all]"
````

2. Create a `.env` file with your AI Core credentials:

```bash
AICORE_AUTH_URL=https://********.authentication.********.hana.ondemand.com
AICORE_CLIENT_ID=********
AICORE_CLIENT_SECRET=********
AICORE_RESOURCE_GROUP=********
AICORE_BASE_URL=https://api.ai.********.hana.ondemand.com/v2
```

## Prerequisites

- SAP BTP subaccount with AI Core (extended plan)
- AI Launchpad (standard plan) for monitoring

## Resources

- [Orchestration Service Docs](https://help.sap.com/doc/generative-ai-hub-sdk/CLOUD/en-US/_reference/orchestration-service.html)
- [Supported Models (SAP Note 3437766)](https://me.sap.com/notes/3437766)
