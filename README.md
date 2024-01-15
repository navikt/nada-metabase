# Metabase

Naisifisert kjøring av Metabase.

## Hemmeligheter

Vi lagrer hemmeligheter for Metabase i Google Secret Manager.
Dette betyr at passordet til databasen hentes fra `MB_DB_PASS`, og ikke fra secreten `google-sql-metabase`.

Disse hemmelighentene er definert i [Google Secret Manager](https://console.cloud.google.com/security/secret-manager/secret/metabase/versions?project=nada-dev-db2e):
```
MB_DB_PASS
MB_PREMIUM_EMBEDDING_TOKEN
MB_SAML_IDENTITY_PROVIDER_CERTIFICATE
MB_SLACK_APP_TOKEN
MB_EMAIL_SMTP_PASSWORD
```
