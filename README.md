# MTA-STS Configuration (Microsoft 365)

This project demonstrates the implementation of MTA-STS for a custom domain using GitHub Pages.

## Components

- SPF, DKIM, DMARC configured on Microsoft 365
- MTA-STS policy hosted via GitHub Pages
- TLS enforced (mode: enforce)

## Key file

/.well-known/mta-sts.txt

## Result

- Secure email transport (TLS enforced)
- Protection against downgrade attacks
- Full email authentication stack implemented
