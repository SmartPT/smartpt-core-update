# SmartPT Core Update Source

Public update source for SmartPT Core installer releases.

## Current Release

- Version: $release
- Tag: $tag
- Installer asset: Setup.exe
- Update manifest: latest.json

## Release Assets

Release assets should be uploaded to GitHub Releases, not committed to the repository history:

- Setup.exe
- Setup.exe.sha256.txt
- console.zip
- dc-frontend.zip
- dc-backend.zip
- jit-frontend.zip
- jit-backend.zip
- erify.zip
- permissions.md
- Remove-SmartPT-Core-Install.ps1

## Update DNS

Point update.smartpt.co.il at this repository or a small static endpoint that serves latest.json.

Recommended stable manifest URL after GitHub Pages is enabled:

https://update.smartpt.co.il/latest.json

## Security Rules

Do not commit customer data, logs, state files, license files, passwords, certificates, or private keys.
Use GitHub Releases for binaries and ZIP payloads.
