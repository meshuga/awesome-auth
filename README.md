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
* [Central Authentication Service (CAS)](https://github.com/apereo/cas) - Open Source Enterprise Single Sign On
* [Okta](https://www.okta.com/) - Identity and Access Management as a service; provides broad integrations
* [Auth0](https://auth0.com/) - Identity and Access Management as a service
* [Cloud-IAM](https://www.cloud-iam.com) - Keycloak IAM as a Service
* [LoginRadius](https://www.loginradius.com/) - Identity and Access Management as a service
* [FusionAuth](https://fusionauth.io/) - Identity and Access Management, either a service or self-hosted
* [PAC4J](http://www.pac4j.org/) - The security library for Java
* [buzzfeed/sso](https://github.com/buzzfeed/sso) - A single sign-on solution for securing internal services (Go based)
* [cidaas](https://www.cidaas.com) - Cloud Identity & Access Management (Identity and Access Management as a service)

#### OAuth
* [RFC6749](https://tools.ietf.org/html/rfc6749) - RFC with OAuth2 definition
* [Spring Security OAuth](http://projects.spring.io/spring-security-oauth/) - OAuth implementation for Spring
* [OAuth server for PHP](http://bshaffer.github.io/oauth2-server-php-docs/) - OAuth server for PHP
* [ORY Hydra](https://www.ory.sh/hydra/) - Go based OAuth and OIDC server
* [JSON Web Tokens](http://jwt.io/) - All you need to know about JWT
* [OAuth+JWT in microservices](https://www.youtube.com/watch?v=BdKmZ7mPNns) - Good video on how to use tokens in microservices
* [OpenID Connect](http://openid.net/connect/) - Identity layer on top of OAuth
* [oauth2-proxy](https://github.com/oauth2-proxy/oauth2-proxy) - A reverse proxy that provides authentication with Google, Github or other providers.

#### SAML
* [SAML](https://en.wikipedia.org/wiki/Security_Assertion_Markup_Language) - Security Assertion Markup Language wiki page
* [Spring Security SAML](http://projects.spring.io/spring-security-saml/) - SAML implementation for Spring
* [SAMLTest](https://samltest.id/) SAML Testing service
* [SAMLkit](https://samlkit.com/) Development/testing entity

### Two-factor authentication
* [U2F and UAF spec](https://fidoalliance.org/specifications/overview/) - 2FA specifications
* [Two Factor Auth](https://twofactorauth.org/) - List of websites with 2FA info

## Passwordless authentication
* [MojoAuth](https://mojoauth.com/) - Email and WebAuthN Authentication
* [Sawolabs](https://sawolabs.com/) - Authentication without OTPs and Passwords

## Authorization
* [Role-based access control](https://en.wikipedia.org/wiki/Role-based_access_control) - wiki page about RBAC
* [XACML](https://en.wikipedia.org/wiki/XACML) - XML-based access control markup language
* [angular-permissions](https://github.com/Narzerus/angular-permission) authorization for AngularJS

## Access management
* [Keycloak](https://www.keycloak.org/) - Open Source Identity and Access Management
* [IdentityServer](https://identityserver.io/) - .NET based IAM server
* [Topaz](https://www.topaz.sh) - Go-native open-source authorization system for cloud-native applications
* [ORY](https://www.ory.sh/) - Open Source Identity Infrastructure and Services (Go based)
* [casbin](https://casbin.org/en/) - Go authorization library
* [OpenAM](https://forgerock.github.io/openam-community-edition/) - (discontinued), successor of OpenSSO
* [WSO2 Identity Server](http://wso2.com/products/identity-server/) - also has SSO, authZ, ...

## Tools
* [Step CLI](https://smallstep.com/cli/) - A zero trust swiss army knife for working with X509, OAuth, JWT, OATH OTP, etc. 
* [JWT DEBUGGER](https://jwt.ssotools.com/)  - A simple JWT decoder tool, that can help to verify the JWT and with the help of signature.

## Other aggregators
* [awesome-keycloak](https://github.com/thomasdarimont/awesome-keycloak) - A curated list of Keycloak related resources
* [casbin/awesome-auth](https://github.com/casbin/awesome-auth) - other auth list
* [OAuth code libraries](https://oauth.net/code/)
* [OIDC code libraries](https://openid.net/developers/libraries/)
