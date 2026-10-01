# Credential detection integration fixture

This repository exists to verify a real GitHub acquisition and detection
workflow for CloudLeakRadar. All apparent credentials are synthetic, unissued,
and deliberately unusable. No cloud account or live authentication credential
is published. Endpoint names illustrate textual association only; access
permissions and public exposure must never be inferred from these strings.

Expected detection: an AWS-shaped identifier, OAuth client secret, PostgreSQL
connection string, and npm-shaped token. The control file contains ordinary
configuration without credentials. Do not use these values for authentication.
