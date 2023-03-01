# pub-sub-api-node-lab

A lab node client which connects with Account standard Change Data Capture Channel. In order to start the hands-on:
1. Create a .env file at the root of the project for configuration with the following information.

> **Warning**<br/>
> Relying on a username/password authentication flow for production is not recommended. Consider switching to JWT auth for extra security.

```properties
SALESFORCE_AUTH_TYPE=username-password
SALESFORCE_LOGIN_URL=https://login.salesforce.com
SALESFORCE_USERNAME=YOUR_SALESFORCE_USERNAME
SALESFORCE_PASSWORD=YOUR_SALESFORCE_PASSWORD
SALESFORCE_TOKEN=YOUR_SALESFORCE_USER_SECURITY_TOKEN

PUB_SUB_ENDPOINT=api.pubsub.salesforce.com:7443
```
2. launch npm start
