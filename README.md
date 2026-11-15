# ATA release trust

Public verification files for Advanced Tracking Academy's member downloads. Nothing here is secret, and nothing here
gives access to anything.

| File | What it is |
|---|---|
| `release-public-key.pub` | ATA's release public key (Ed25519, PEM). The same key is published on the ATA site and shown in the course. |
| `ata-release.json` | The signed trust file: which connection script is current and the minimum versions. |
| `ata-release.json.sig` | Its signature, base64. |

The ATA connection script checks these files against the key it already holds before it installs anything. Only paste
the connection prompt from your ATA account page.
