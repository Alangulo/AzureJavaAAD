---

endpoint: AAD V1
---
# Integrating Azure AD into a Java web application

## About this sample

### Overview

This sample demonstrates a Java web application calling a Microsoft Graph that is secured using Azure Active Directory.

1. The Java web application uses the Active Directory Authentication Library for Java(ADAL4J) to obtain a JWT access token from Azure Active Directory (Azure AD):
2. The access token is used as a bearer token to authenticate the user when calling the Microsoft Graph.


### Scenario

This sample shows how to build a Java web app(confidential client) that uses OpenID Connect to sign-in users from a single Azure Active Directory (Azure AD) tenant using ADAL4J. For more information about how the protocols work in this scenario and other scenarios, see [Authentication Scenarios for Azure AD](https://docs.microsoft.com/en-us/azure/active-directory/develop/active-directory-authentication-scenarios).
