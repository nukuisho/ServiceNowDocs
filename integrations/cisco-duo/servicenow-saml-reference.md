# ServiceNow and Cisco Duo SAML reference

This note collects the external resources and implementation checkpoints for configuring Cisco Duo Single Sign-On as the SAML identity provider for a ServiceNow instance.

## Recommended integration path

Use **Duo Single Sign-On for ServiceNow** as the primary reference for this project. Duo provides a ServiceNow application in the Duo application catalog, and the documented setup imports Duo IdP metadata into ServiceNow Multi-Provider SSO.

Use **Generic SAML Service Provider** only as a fallback when the catalog ServiceNow application cannot satisfy a requirement. Use the **Duo Auth API** and SDK repositories only for non-SAML API automation or custom Duo API integrations; they are not required for a standard ServiceNow SAML SSO setup.

## ServiceNow-side references in this repository

- `markdown/platform-security/authentication/c_SAML2.0WebBrowserSSOProfile.md` explains that SAML exchanges authentication data between an IdP and SP, and that ServiceNow logs in a user when the SAML `NameID` matches a user record.
- `markdown/platform-security/authentication/t_CreateUpdateIdentityProvider.md` describes creating or updating a Multi-Provider SSO identity provider and importing SAML IdP metadata.
- `markdown/platform-security/authentication/configure-servicenow.md` includes ServiceNow SAML setup details such as choosing SAML, importing IdP metadata by URL or XML, and advanced metadata URL behavior.

## External documentation links for live lookup

| Resource | URL | When to use |
| --- | --- | --- |
| Duo Single Sign-On for ServiceNow | https://duo.com/docs/sso-servicenow | Primary implementation guide for ServiceNow + Duo SAML SSO. |
| Duo Single Sign-On documentation | https://duo.com/docs/sso | Background on Duo SSO, authentication sources, routing rules, and Duo-hosted SSO behavior. |
| Generic SAML Service Provider Guide | https://duo.com/docs/sso-generic | Fallback guide if the catalog ServiceNow SAML application is not used. |
| Duo Auth API Documentation | https://duo.com/docs/authapi | Reference for low-level Duo REST API work; not needed for normal SAML SSO configuration. |

## GitHub repositories for live lookup

These repositories are intentionally listed as live references instead of vendored into this repository. A SAML SSO configuration does not require application code from these projects, and keeping them as links avoids stale copies of security-sensitive client code.

| Repository | URL | Relevance |
| --- | --- | --- |
| `duo_client_python` | https://github.com/duosecurity/duo_client_python | Python client for Duo Auth, Admin, and Accounts APIs. Use only if project scope expands to Duo API automation. |
| `duo_api_golang` | https://github.com/duosecurity/duo_api_golang | Go bindings for Duo Auth and Admin APIs. Use only if Go-based Duo API automation is required. |
| `duo_unix` | https://github.com/duosecurity/duo_unix | Duo two-factor authentication for Unix systems. Not part of ServiceNow SAML SSO; keep for contextual reference only. |

## Implementation checkpoints

1. Confirm ServiceNow Multi-Provider SSO is installed and enabled.
2. Confirm the identifier used by Duo maps to a populated ServiceNow user field. Duo's ServiceNow guide uses the user's email address by default.
3. In Duo, create the ServiceNow SSO application from the application catalog where possible.
4. In ServiceNow, create a SAML identity provider and import Duo IdP metadata by XML or URL.
5. Configure the ServiceNow instance name or service provider values in Duo.
6. Test the connection with a controlled pilot user before enabling SSO for all users.
7. Document rollback access for local admin users before enabling auto-redirect or broad SSO enforcement.

## Notes and cautions

- Do not treat the Auth API as a substitute for SAML SSO. The Auth API is for custom API-driven two-factor flows and is a separate integration pattern.
- Do not vendor Duo SDK repositories unless implementation requires code-level API automation; link to the upstream repositories instead.
- Re-check Cisco Duo documentation during implementation because Duo SSO and API documents are updated frequently.
