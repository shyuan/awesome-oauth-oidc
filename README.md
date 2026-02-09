# Awesome OAuth 2.0 and OpenID Connect

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> A curated list of resources for OAuth 2.0 and OpenID Connect (OIDC) — specifications, articles, books, playgrounds, and more.

## Contents

- [Site](#site)
- [Specification](#specification)
- [Article](#article)
- [Book](#book)
- [Server Implementation](#server-implementation)
- [Client Library](#client-library)
- [Tool](#tool)
- [Video](#video)
- [Social Media](#social-media)
- [Community](#community)

## Site
* [OAuth on Wikipedia](https://en.wikipedia.org/wiki/OAuth)
* [OAuth.net by Okta](https://oauth.net/)
* [OAuth.com by Okta](https://www.oauth.com/)
* [OAuth Articles and Posts by Alex Bilbie](https://alexbilbie.com/tag/oauth/)
* [OpenID Connect](https://openid.net/connect/)

## Specification

### IETF RFC
* [The OAuth 2.0 Authorization Framework (RFC 6749)](https://datatracker.ietf.org/doc/html/rfc6749)
* [The OAuth 2.0 Authorization Framework: Bearer Token Usage (RFC 6750)](https://datatracker.ietf.org/doc/html/rfc6750)
* [OAuth 2.0 Threat Model and Security Considerations (RFC 6819)](https://datatracker.ietf.org/doc/html/rfc6819)
* [OAuth 2.0 Token Revocation (RFC 7009)](https://datatracker.ietf.org/doc/html/rfc7009)
* [WebFinger (RFC 7033)](https://datatracker.ietf.org/doc/html/rfc7033)
* [JSON Web Signature (JWS) (RFC 7515)](https://datatracker.ietf.org/doc/html/rfc7515)
* [JSON Web Encryption (JWE) (RFC 7516)](https://datatracker.ietf.org/doc/html/rfc7516)
* [JSON Web Key (JWK) (RFC 7517)](https://datatracker.ietf.org/doc/html/rfc7517)
* [JSON Web Algorithms (JWA) (RFC 7518)](https://datatracker.ietf.org/doc/html/rfc7518)
* [JSON Web Token (JWT) (RFC 7519)](https://datatracker.ietf.org/doc/html/rfc7519)
* [Examples of Protecting Content Using JSON Object Signing and Encryption (JOSE) (RFC 7520)](https://datatracker.ietf.org/doc/html/rfc7520)
* [Assertion Framework for OAuth 2.0 Client Authentication and Authorization Grants (RFC 7521)](https://datatracker.ietf.org/doc/html/rfc7521)
* [SAML 2.0 Profile for OAuth 2.0 Client Authentication and Authorization Grants (RFC 7522)](https://datatracker.ietf.org/doc/html/rfc7522)
* [JSON Web Token (JWT) Profile for OAuth 2.0 Client Authentication and Authorization Grants (RFC 7523)](https://datatracker.ietf.org/doc/html/rfc7523)
* [OAuth 2.0 Dynamic Client Registration Protocol (RFC 7591)](https://datatracker.ietf.org/doc/html/rfc7591)
* [OAuth 2.0 Dynamic Client Registration Management Protocol (RFC 7592)](https://datatracker.ietf.org/doc/html/rfc7592)
* [Proof Key for Code Exchange by OAuth Public Clients (RFC 7636)](https://datatracker.ietf.org/doc/html/rfc7636)
* [OAuth 2.0 Token Introspection (RFC 7662)](https://datatracker.ietf.org/doc/html/rfc7662)
* [JSON Web Signature (JWS) Unencoded Payload Option (RFC 7797)](https://datatracker.ietf.org/doc/html/rfc7797)
* [Authentication Method Reference Values (RFC 8176)](https://datatracker.ietf.org/doc/html/rfc8176)
* [OAuth 2.0 for Native Apps (RFC 8252)](https://datatracker.ietf.org/doc/html/rfc8252)
* [OAuth 2.0 Authorization Server Metadata (RFC 8414)](https://datatracker.ietf.org/doc/html/rfc8414)
* [Security Event Token (SET) (RFC 8417)](https://datatracker.ietf.org/doc/html/rfc8417)
* [Vectors of Trust (RFC 8485)](https://datatracker.ietf.org/doc/html/rfc8485)
* [OAuth 2.0 Device Authorization Grant (RFC 8628)](https://datatracker.ietf.org/doc/html/rfc8628)
* [OAuth 2.0 Token Exchange (RFC 8693)](https://datatracker.ietf.org/doc/html/rfc8693)
* [OAuth 2.0 Mutual TLS Client Authentication and Certificate-Bound Access Tokens (RFC 8705)](https://datatracker.ietf.org/doc/html/rfc8705)
* [JSON Web Token Best Current Practices (RFC 8725)](https://datatracker.ietf.org/doc/html/rfc8725)
* [Push-Based Security Event Token (SET) Delivery Using HTTP (RFC 8935)](https://datatracker.ietf.org/doc/html/rfc8935)
* [Poll-Based Security Event Token (SET) Delivery Using HTTP (RFC 8936)](https://datatracker.ietf.org/doc/html/rfc8936)
* [JSON Web Token (JWT) Profile for OAuth 2.0 Access Tokens (RFC 9068)](https://datatracker.ietf.org/doc/html/rfc9068)
* [The OAuth 2.0 Authorization Framework: JWT-Secured Authorization Request (JAR) (RFC 9101)](https://datatracker.ietf.org/doc/html/rfc9101)
* [OAuth 2.0 Pushed Authorization Requests (RFC 9126)](https://datatracker.ietf.org/doc/html/rfc9126)
* [OAuth 2.0 Authorization Server Issuer Identification (RFC 9207)](https://datatracker.ietf.org/doc/html/rfc9207)
* [JWK Thumbprint URI (RFC 9278)](https://datatracker.ietf.org/doc/html/rfc9278)
* [OAuth 2.0 Rich Authorization Requests (RFC 9396)](https://datatracker.ietf.org/doc/html/rfc9396)
* [Client-Cert HTTP Header Field (RFC 9440)](https://datatracker.ietf.org/doc/html/rfc9440)
* [OAuth 2.0 Demonstrating Proof of Possession (DPoP) (RFC 9449)](https://datatracker.ietf.org/doc/html/rfc9449)
* [OAuth 2.0 Step Up Authentication Challenge Protocol (RFC 9470)](https://datatracker.ietf.org/doc/html/rfc9470)
* [Subject Identifiers for Security Event Tokens (RFC 9493)](https://datatracker.ietf.org/doc/html/rfc9493)
* [OAuth 2.0 Security Best Current Practice (RFC 9700)](https://datatracker.ietf.org/doc/html/rfc9700)
* [Selective Disclosure for JSON Web Tokens (SD-JWT) (RFC 9901)](https://datatracker.ietf.org/doc/html/rfc9901)

### IETF Draft
#### Active
* [OAuth 2.0 for Browser-Based Apps (draft-ietf-oauth-browser-based-apps-26)](https://datatracker.ietf.org/doc/html/draft-ietf-oauth-browser-based-apps-26)
* [The OAuth 2.1 Authorization Framework (draft-ietf-oauth-v2-1-14)](https://datatracker.ietf.org/doc/html/draft-ietf-oauth-v2-1-14)
* [Cross-Device Flows: Security Best Current Practice (draft-ietf-oauth-cross-device-security-15)](https://datatracker.ietf.org/doc/html/draft-ietf-oauth-cross-device-security-15)
* [OAuth Identity and Authorization Chaining Across Domains (draft-ietf-oauth-identity-chaining-07)](https://datatracker.ietf.org/doc/html/draft-ietf-oauth-identity-chaining-07)
* [SD-JWT-based Verifiable Digital Credentials (draft-ietf-oauth-sd-jwt-vc-14)](https://datatracker.ietf.org/doc/html/draft-ietf-oauth-sd-jwt-vc-14)
* [Token Status List (draft-ietf-oauth-status-list-17)](https://datatracker.ietf.org/doc/html/draft-ietf-oauth-status-list-17)
* [Transaction Tokens (draft-ietf-oauth-transaction-tokens-07)](https://datatracker.ietf.org/doc/html/draft-ietf-oauth-transaction-tokens-07)

#### Expired & archived
* [Reciprocal OAuth (draft-ietf-oauth-reciprocal-04)](https://datatracker.ietf.org/doc/html/draft-ietf-oauth-reciprocal-04)
* [OAuth 2.0 Token Binding (draft-ietf-oauth-token-binding-08)](https://datatracker.ietf.org/doc/html/draft-ietf-oauth-token-binding-08)
* [OAuth 2.0 Incremental Authorization (draft-ietf-oauth-incremental-authz-04)](https://datatracker.ietf.org/doc/html/draft-ietf-oauth-incremental-authz-04)

### OpenID Connect
* [OpenID Connect Core 1.0](https://openid.net/specs/openid-connect-core-1_0.html)
* [OpenID Connect Discovery 1.0](https://openid.net/specs/openid-connect-discovery-1_0.html)
* [OpenID Connect Dynamic Client Registration 1.0](https://openid.net/specs/openid-connect-registration-1_0.html)
* [OAuth 2.0 Multiple Response Types](https://openid.net/specs/oauth-v2-multiple-response-types-1_0.html)
* [OAuth 2.0 Form Post Response Mode](https://openid.net/specs/oauth-v2-form-post-response-mode-1_0.html)
* [OpenID Connect RP-Initiated Logout 1.0](https://openid.net/specs/openid-connect-rpinitiated-1_0.html)
* [OpenID Connect Session Management 1.0](https://openid.net/specs/openid-connect-session-1_0.html)
* [OpenID Connect Front-Channel Logout 1.0](https://openid.net/specs/openid-connect-frontchannel-1_0.html)
* [OpenID Connect Back-Channel Logout 1.0](https://openid.net/specs/openid-connect-backchannel-1_0.html)
* [OpenID Connect Federation 1.0](https://openid.net/specs/openid-connect-federation-1_0.html)
* [OpenID Connect for Identity Assurance 1.0](https://openid.net/specs/openid-connect-4-identity-assurance-1_0.html)

### CIBA
* [OpenID Connect CIBA Flow - Core 1.0](https://openid.net/specs/openid-client-initiated-backchannel-authentication-core-1_0.html)

### FAPI
* [FAPI 2.0 Security Profile](https://openid.net/specs/fapi-security-profile-2_0.html)
* [FAPI 2.0 Message Signing](https://openid.net/specs/fapi-2_0-message-signing.html)
* [FAPI 2.0 Attacker Model](https://openid.net/specs/fapi-2_0-attacker-model.html)
* [JWT Secured Authorization Response Mode (JARM)](https://openid.net/specs/oauth-v2-jarm.html)
* [Grant Management for OAuth 2.0](https://openid.net/specs/fapi-grant-management.html)

## Article
* OAuth 2.0 系列文 by [Yucheng Chuang](https://x.com/yorkxin)
    * [(1) 世界觀](https://blog.yorkxin.org/posts/oauth2-1-introduction/)
    * [(2) Client 的註冊與認證](https://blog.yorkxin.org/posts/oauth2-2-cilent-registration/)
    * [(3) Endpoints 的規格](https://blog.yorkxin.org/posts/oauth2-3-endpoints/)
    * [(4.1) Authorization Code Grant Flow 細節](https://blog.yorkxin.org/posts/oauth2-4-1-auth-code-grant-flow)
    * [(4.2) Implicit Grant Flow 細節](https://blog.yorkxin.org/posts/oauth2-4-2-implicit-grant-flow)
    * [(4.3) Resource Owner Credentials Grant Flow 細節](https://blog.yorkxin.org/posts/oauth2-4-3-resource-owner-credentials-grant-flow)
    * [(4.4) Client Credentials Grant Flow 細節](https://blog.yorkxin.org/posts/oauth2-4-4-client-credentials-grant-flow)
    * [(5) 核發與換發 Access Token](https://blog.yorkxin.org/posts/oauth2-5-issuing-tokens)
    * [(6) Bearer Token 的使用方法](https://blog.yorkxin.org/posts/oauth2-6-bearer-token)
    * [(7) 安全性問題](https://blog.yorkxin.org/posts/oauth2-7-security-considerations)
    * [各大網站 OAuth 2.0 實作差異](https://blog.yorkxin.org/posts/oauth2-implementation-differences-among-famous-sites)
* [OAuth 2 Simplified by Aaron Parecki](https://aaronparecki.com/oauth-2-simplified/)
* [理解OAuth 2.0 by 阮一峰](https://www.ruanyifeng.com/blog/2014/05/oauth_2_0.html)
* [帮你深入理解OAuth2.0协议](https://blog.csdn.net/seccloud/article/details/8192707)
* [What's OAuth2 Anyway? by Roman Glushko](https://www.romaglushko.com/blog/whats-aouth2/)

## Book
* [OAuth 2 in Action](https://www.manning.com/books/oauth-2-in-action)
* [Getting Started with OAuth 2.0 - Programming Clients for Secure Web API Authorization and Authentication](https://www.oreilly.com/library/view/~/9781449317843/)
* [Identity and Data Security for Web Development - Best Practices](https://www.oreilly.com/library/view/~/9781491937006/)
* [OAuth 2.0 – Getting Started in Web-API Security](https://api-university.com/books/oauth-2-0-book/)

## Server Implementation
* [Keycloak](https://www.keycloak.org/) - Open-source IAM by Red Hat, supports OAuth 2.0, OIDC, and SAML 2.0 (Java)
* [Ory Hydra](https://github.com/ory/hydra) - Headless, cloud-native OAuth 2.0 and OIDC server, OpenID Certified (Go)
* [Dex](https://github.com/dexidp/dex) - Federated OIDC provider by CNCF, widely used in the Kubernetes ecosystem (Go)
* [Authentik](https://goauthentik.io/) - Self-hosted identity provider supporting OAuth 2.0, OIDC, SAML, SCIM, and LDAP (Python/Go)
* [Authelia](https://www.authelia.com/) - Authentication and SSO server with OIDC Identity Provider support (Go)
* [node-oidc-provider](https://github.com/panva/node-oidc-provider) - Certified OpenID Connect provider for Node.js (JavaScript)
* [Spring Authorization Server](https://spring.io/projects/spring-authorization-server) - Official Spring project for OAuth 2.0 and OIDC Authorization Servers (Java)
* [OpenIddict](https://github.com/openiddict/openiddict-core) - Flexible open-source OIDC server for ASP.NET Core (.NET)
* [ZITADEL](https://zitadel.com/) - Cloud-native identity management with OAuth 2.0 and OIDC (Go)
* [Logto](https://logto.io/) - Developer-friendly, open-source Auth0 alternative with OIDC support (TypeScript)
* [Casdoor](https://casdoor.org/) - UI-first IAM platform supporting OAuth 2.0, OIDC, SAML, CAS, and more (Go)

## Client Library

### Go
* [golang.org/x/oauth2](https://github.com/golang/oauth2) - Official Go OAuth 2.0 client library
* [go-oidc](https://github.com/coreos/go-oidc) - OpenID Connect support for Go, built on golang.org/x/oauth2

### JavaScript / TypeScript
* [openid-client](https://github.com/panva/openid-client) - Certified OpenID Connect Relying Party for Node.js
* [jose](https://github.com/panva/jose) - Universal JavaScript module for JWS, JWE, JWT, JWK, and JWKS
* [passport](https://github.com/jaredhanson/passport) - Authentication middleware for Node.js with OAuth 2.0 / OIDC strategies
* [arctic](https://github.com/pilcrowonpaper/arctic) - OAuth 2.0 provider helpers for 50+ providers with minimal abstraction

### Python
* [Authlib](https://github.com/lepture/authlib) - OAuth and OIDC client/server library for Flask, Django, FastAPI, and more
* [OAuthLib](https://github.com/oauthlib/oauthlib) - Generic, spec-compliant OAuth request-signing logic
* [requests-oauthlib](https://github.com/requests/requests-oauthlib) - OAuth support for Python `requests`, built on OAuthLib
* [PyJWT](https://github.com/jpadilla/pyjwt) - JSON Web Token encoding and decoding

### Java
* [Nimbus JOSE + JWT](https://connect2id.com/products/nimbus-jose-jwt) - Popular Java library for JOSE and JWT
* [Nimbus OAuth 2.0 SDK](https://connect2id.com/products/nimbus-oauth-openid-connect-sdk) - Comprehensive OAuth 2.0 and OpenID Connect SDK
* [ScribeJava](https://github.com/scribejava/scribejava) - Simple OAuth 1.0 / 2.0 client library

### Rust
* [oauth2-rs](https://github.com/ramosbugs/oauth2-rs) - Extensible, strongly-typed OAuth 2.0 client
* [openidconnect-rs](https://github.com/ramosbugs/openidconnect-rs) - OpenID Connect library built on oauth2-rs

### .NET
* [Duende IdentityServer](https://github.com/DuendeSoftware/IdentityServer) - OAuth 2.0 and OIDC framework for ASP.NET Core (free for dev/OSS)
* [Microsoft.Identity.Web](https://github.com/AzureAD/microsoft-identity-web) - Microsoft Identity integration for ASP.NET Core

### PHP
* [league/oauth2-server](https://github.com/thephpleague/oauth2-server) - Standards-compliant OAuth 2.0 authorization server
* [league/oauth2-client](https://github.com/thephpleague/oauth2-client) - OAuth 2.0 client library

### Ruby
* [Doorkeeper](https://github.com/doorkeeper-gem/doorkeeper) - OAuth 2.0 provider for Ruby on Rails
* [OmniAuth](https://github.com/omniauth/omniauth) - Multi-provider authentication framework

## Tool

### Playground
* [OAUTH.TOOLS](https://oauth.tools/) - Interactive OAuth/OIDC playground by Curity
* [Google OAuth 2.0 Playground](https://developers.google.com/oauthplayground/)
* [OIDC Playground](https://oidc-playground.compile7.org/)
* [OIDC Debugger](https://oidcdebugger.com/) - Web-based tool for testing OIDC authorization requests
* [OpenID Connect Conformance Suite](https://openid.net/certification/testing/) - Official OIDC provider conformance test suite

### JWT
* [jwt.io](https://jwt.io/) - JWT debugger and library directory by Auth0
* [jwt.ms](https://jwt.ms/) - JWT decoder by Microsoft
* [token.dev](https://token.dev/) - Modern JWT debugger with a clean interface
* [mkjwk.org](https://mkjwk.org/) - JSON Web Key (JWK) generator
* [jwt-cli](https://github.com/mike-engel/jwt-cli) - Command-line JWT decoder/encoder (Rust)

### CLI
* [oauth2c](https://github.com/cloudentity/oauth2c) - Command-line OAuth 2.0 client supporting all grant types, PKCE, DPoP, mTLS
* [step-cli](https://github.com/smallstep/cli) - CLI for certificates, tokens, and OIDC flows

## Video
* [OAuth 2.0 and OpenID Connect (in plain English) by Nate Barbettini](https://www.youtube.com/watch?v=996OiexHze0)
* [An Illustrated Guide to OAuth and OpenID Connect by OktaDev](https://www.youtube.com/watch?v=t18YB3xDfXI)
* [The Nuts and Bolts of OAuth 2.0 by Aaron Parecki](https://www.youtube.com/watch?v=CPbvxxslDTU)

## Social Media
* [OAuth 2.0 Explained by Alex Xu (ByteByteGo)](https://x.com/alexxubyte/status/1696180531266715815)

## Community
* [IETF OAuth Working Group Mailing List](https://mailarchive.ietf.org/arch/browse/oauth/) - Where OAuth specifications are discussed and developed
* [OpenID Foundation](https://openid.net/foundation/) - Organization behind OpenID Connect standards and certification
* [Identiverse](https://identiverse.com/) - Premier annual conference on digital identity
