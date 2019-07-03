# awesome-auth
A curated list of awesome AuthN+Z libraries, services and resources.

## Cloud solutions

### Amazon Web Services (AWS)
* [AWS IAM](https://aws.amazon.com/iam/) - Identity and Access Management for AWS
* [AWS SSO](https://aws.amazon.com/single-sign-on/) - Centrally manage single sign-on (SSO) access to multiple AWS accounts
* [Amazon Cognito](https://aws.amazon.com/cognito/) - SSO for business applications
* [AWS Directory Service](https://aws.amazon.com/directoryservice/) - AD in the AWS Cloud
* [AWS STS](https://docs.aws.amazon.com/STS/latest/APIReference/Welcome.html) - AWS Security Token Service for temporary IAM tokens

### Google Cloud Platform (GCP)
* [Identity and authentication, the Google Cloud way](https://cloud.google.com/blog/products/identity-security/identity-and-authentication-the-google-cloud-way) - Overview of Google approach to identity and access management

### Microsoft Azure
* [Microsoft identity platform](https://docs.microsoft.com/en-us/azure/active-directory/develop/) - Evolution of the Azure Active Directory

## Authentication

### SSO
* [Single sign-on](https://en.wikipedia.org/wiki/Single_sign-on) - wiki page about SSO
* [Okta](https://www.okta.com/) - Identity and Access Management as a service; provides broad integrations
* [Auth0](https://auth0.com/) - Identity and Access Management as a service
* [PAC4J](http://www.pac4j.org/) - The security library for Java

#### OAuth
* [RFC6749](https://tools.ietf.org/html/rfc6749) - RFC with OAuth2 definition
* [IdentityServer3](https://github.com/IdentityServer/IdentityServer3) - OAuth server
* [Spring Security OAuth](http://projects.spring.io/spring-security-oauth/) - OAuth implementation for Spring
* [OAuth server for PHP](http://bshaffer.github.io/oauth2-server-php-docs/) - OAuth server for PHP
* [JSON Web Tokens](http://jwt.io/) - All you need to know about JWT
* [OAuth+JWT in microservices](https://www.youtube.com/watch?v=BdKmZ7mPNns) - Good video on how to use tokens in microservices
* [OpenID Connect](http://openid.net/connect/) - Identity layer on top of OAuth

#### SAML
* [SAML](https://en.wikipedia.org/wiki/Security_Assertion_Markup_Language) - Security Assertion Markup Language wiki page
* [Spring Security SAML](http://projects.spring.io/spring-security-saml/) - SAML implementation for Spring

### Two-factor authentication
* [U2F and UAF spec](https://fidoalliance.org/specifications/overview/) - 2FA specifications
* [Two Factor Auth](https://twofactorauth.org/) - List of websites with 2FA info

## Authorization
* [Role-based access control](https://en.wikipedia.org/wiki/Role-based_access_control) - wiki page about RBAC
* [XACML](https://en.wikipedia.org/wiki/XACML) - XML-based access control markup language
* [angular-permissions](https://github.com/Narzerus/angular-permission) authorization for AngularJS

## Access management
* [Keycloak](https://www.keycloak.org/) - Open Source Identity and Access Management
* [casbin](https://casbin.org/en/) - Go authorization library
* [OpenAM](https://forgerock.github.io/openam-community-edition/) - (discontinued), successor of OpenSSO
* [WSO2 Identity Server](http://wso2.com/products/identity-server/) - also has SSO, authZ, ...