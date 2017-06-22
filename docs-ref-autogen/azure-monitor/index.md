# Microsoft Azure SDK for Node.js - Azure Monitor Management

This project provides a Node.js package that makes it easy to use the Azure Monitor API. Right now it supports:
- **Node.js version: 0.6.15 or higher**
- **API version: 2014-04-01, 2015-04-01, 2016-03-01, 2016-09-01, 2017-05-01-preview **

## How to Install

```bash
npm install azure-monitor
```

## How to Use

### Authentication

 ```javascript
 var msRestAzure = require('ms-rest-azure');
 var monitorClient = require('azure-monitor');
 
 // Interactive Login
 msRestAzure.interactiveLogin(function(err, credentials) {
   var client = new monitorClient(credentials, 'your-subscription-id');
 });
 ```

### Create the monitorClient

```javascript
 var msRestAzure = require("ms-rest-azure"),
 var monitorClient = require("azure-monitor");

 var client = new monitorClient(credentials, 'your subscription id');
```

## Related projects

- [Microsoft Azure SDK for Node.js - All-up](https://github.com/WindowsAzure/azure-sdk-for-node)
