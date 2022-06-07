# Metabase

Enkel POC av [Metabase](https://www.metabase.com/) som et analyseverktøy, ala Superset og Tableau.

## Deployment

### Hemmeligheter

Hemmeligheter er lagret i Google Secret Manager. Dette betyr at database credentials må kopieres fra `google-sql-metabase` til `metabase` i GSM.

Følgende hemmeligheter bruker vi:
```
MB_DB_CONNECTION_URI
MB_PREMIUM_EMBEDDING_TOKEN
MB_SAML_IDENTITY_PROVIDER_CERTIFICATE
MB_SAML_IDENTITY_PROVIDER_ISSUER
MB_SAML_IDENTITY_PROVIDER_URI
```
