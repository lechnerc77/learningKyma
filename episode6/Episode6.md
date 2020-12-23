# Learning Kyma - Episode 6

## Content

This session we take a look into Kyma and security. There are two main learning goals:

* Understand which components of Kyma are relevant in the context of security and what are their responsibility
* Secure an API endpoint with OAuth2

In addition we will take a quick glance at the topics SAML2, OAuth2.0 and OpenID Connect. 

## Sessions on YouTube

You find this session on YouTube here: [Link](https://youtu.be/psaBBYeMAeo)

## References

### Security in Kyma - Overview

* [Kyma Component - Security](https://kyma-project.io/docs/components/security)

### Dex and IdP Federation

* [Dex - A Federated OpenID Connect Provider](https://dexidp.io/)
  * [Dex Connectors](https://github.com/dexidp/dex#connectors)
  * [Kyma - Add an Identity Provider to Dex](https://kyma-project.io/docs/components/security#tutorials-add-an-identity-provider-to-dex)
  * [Kyma - Post-installation changes](https://kyma-project.io/docs/#configuration-custom-component-installation-post-installation-changes)

### Basics about SAML and OAuth

* [SAML V2.0 - Specification](http://docs.oasis-open.org/security/saml/Post2.0/sstc-saml-tech-overview-2.0.html)
* [What is SAML and How Does it Work?](https://www.varonis.com/blog/what-is-saml/)
* [OAuth 2.0 - Landing Page](https://oauth.net/2/)
  * [What the Heck is OAuth?](https://developer.okta.com/blog/2017/06/21/what-the-heck-is-oauth)
  * [What the Heck is OAuth? - OAuth Tokens](https://developer.okta.com/blog/2017/06/21/what-the-heck-is-oauth#oauth-tokens)
  * [What the Heck is OAuth? - OAuth Flows](https://developer.okta.com/blog/2017/06/21/what-the-heck-is-oauth#oauth-flows)
* [Welcome to OpenID Connect](https://openid.net/connect/)

### Securing API endpoints with Kyma

* [API Gateway](https://kyma-project.io/docs/components/api-gateway/)
  * [API Rule](https://kyma-project.io/docs/components/api-gateway#custom-resource-api-rule)
* [ORY - Open Source Identity Infrastructure and Services](https://www.ory.sh/)
  * [ORY Oathkeeper](https://www.ory.sh/oathkeeper/docs/)
    * [ORY Oathkeeper - Mutators](https://www.ory.sh/oathkeeper/docs/pipeline/mutator)
    * [ORY Oathkeeper - Authenticators](https://www.ory.sh/oathkeeper/docs/pipeline/authn)
  * [ORY Hydra](https://www.ory.sh/hydra/docs/)
    * [ORY Hydra - Creating OAuth Clients via CLI](https://www.ory.sh/hydra/docs/guides/oauth2-clients/)
    * [ORY Hydra - Creating OAuth Clients via YAML](https://github.com/ory/hydra-maester/blob/3fa0cc3b666867f95ff6ea64dc181d5165c6370d/config/samples/hydra_v1alpha1_oauth2client_user_credentials.yaml)
* [Kyma for Dymmies [2]: First Simple Microservice with Security](https://blogs.sap.com/2020/12/10/kyma-for-dymmies-2-first-simple-microservice-with-security/)
* [Kyma for Dymmies [3]: calling secured service with REST client](https://blogs.sap.com/2020/12/14/kyma-for-dymmies-3-calling-secured-service-with-rest-client/)
* [GitHub repository with source code for Kyma for Dymmies blog posts 2 + 3](https://github.com/lechnerc77/kyma_for_dymmies_2_and_3)