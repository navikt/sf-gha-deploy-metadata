# sf-gha-deploy-metadata

GitHub action for å deploye metadata til en Salesforce org med SF CLI

## Bruk

<!-- Start usage -->
```yaml
- uses: navikt/sf-gha-deploy-metadata@<tag/sha>
  with:
    # Path to metadata
    # Required: true
    path: 'force-app/unpackagable-with-auto-deploy'
    
    # Target org alias or username
    # Required: true
    target-org: 'my-target-org'
    
    # Is validation and not deployment
    # Required: false
    # Default: "false"
    validate-only: 'false'
```
<!-- end usage -->

## Henvendelser

Spørsmål knyttet til koden eller prosjektet kan stilles som issues her på GitHub.

## For NAV-ansatte

Interne henvendelser kan sendes via Slack i kanalen #platforce.
