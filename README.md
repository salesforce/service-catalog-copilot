# Title

This repository contains sample catalog items for Einstein Copilot.

## Installation

### Use Salesforce CLI

1. Install [Salesforce CLI](https://developer.salesforce.com/tools/salesforcecli)
2. Connect Salesforce CLI to your org: 
* `sf org login web --alias yourOrgAlias --instance-url https://yourOrg.sandbox.my.salesforce.com` 
* Use domain URL found in Setup > Company Settings > My Domain
3. Deploy Service Catalog Copilot metadata: 
* `sf project deploy start --source-dir force-app --target-org yourOrgAlias`