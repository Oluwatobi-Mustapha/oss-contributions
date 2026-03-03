## Open Source Contributions

A curated list of my merged open-source pull requests, focusing on identity infrastructure and security.

1. [Patched a TOCTOU race condition in OTP verification to prevent token reuse under concurrent requests in `better-auth`](https://github.com/better-auth/better-auth/pull/8067)

2. [Fixed a multi-session identity transition failure by implementing strict server-side cryptographic cookie validation in `better-auth`](https://github.com/better-auth/better-auth/pull/8121)

3. [Restored identity persistence by properly decoding Set-Cookie values to prevent cryptographic cookie double-encoding during session refreshes in `better-auth`](https://github.com/better-auth/better-auth/pull/8133)

4. [Did an IAM Security review and enforced fixes in `leapstacks2`](https://github.com/bfateen/leapstacks2)
