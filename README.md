# Open Source Contributions

A curated list of my merged open-source pull requests, focusing on identity infrastructure and security.

1. [Engineered OpenID for Verifiable Credential Issuance (OID4VCI) flow updates to support `credential_configuration_id` processing in `keycloak`](https://github.com/keycloak/keycloak/pull/46690)
  
2. [Fixed a multi-session identity transition failure by implementing strict server-side cryptographic cookie validation in `better-auth`](https://github.com/better-auth/better-auth/pull/8121)

3. [Hardened identity federation by decoupling localized UI labels from backend persistence to enforce strict OIDC protocol compliance in `keycloak`](https://github.com/keycloak/keycloak/pull/46880)

4. [Restored identity persistence by properly decoding Set-Cookie values to prevent cryptographic cookie double-encoding during session refreshes in `better-auth`](https://github.com/better-auth/better-auth/pull/8133)

5. [Patched a TOCTOU race condition in OTP verification to prevent token reuse under concurrent requests in `better-auth`](https://github.com/better-auth/better-auth/pull/8067)

6. [Did an IAM Security review and enforced fixes in `leapstacks2`](https://github.com/bfateen/leapstacks2)
