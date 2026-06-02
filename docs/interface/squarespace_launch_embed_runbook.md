# Squarespace Launch Embed Runbook

Status: L1 public-safe preview artifact

## Artifact

Use:

```text
dashboard_widgets/squarespace_launch_embed.html
```

This file is self-contained for a Squarespace Code Block:
- inline CSS
- inline JavaScript
- inline public-safe demo data
- no raw Google Sheets endpoint
- no private Drive link exposure
- no wallet, token, mint, IPFS, or live registry activation

## Placement

Recommended first placement:

| Squarespace page | Embed |
|---|---|
| `/library` | `dashboard_widgets/squarespace_launch_embed.html` |
| `/collective/dashboard` | same embed, private or unlisted until member flow is ready |

## Launch Boundary

Allowed in this L1 block:
- public-safe hierarchy overview
- scaffold collective and sub-collective rows
- launch gate status
- redacted demo-only data

Not allowed in this L1 block:
- private member records
- live Drive folder listings
- live Sheets rows
- investment, dividend, guaranteed-return, or securities framing
- wallet, token, mint, IPFS, or live registry workflows

## Next Build Step

Move from inline demo data to a reviewed dashboard export only after:
- the public dashboard field allowlist is applied
- the export is static or served from an approved endpoint
- private/member rows are confirmed excluded
- the launch gate remains at L1 or L2, not live mint

