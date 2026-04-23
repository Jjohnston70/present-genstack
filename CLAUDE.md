# CLAUDE.md

## Repo Intent
`present-genstack` is a branded, public-facing Python tool that generates clean HTML presentations from project README files.

## Primary Outcomes
- Keep source code lightweight, readable, and dependency-minimal.
- Keep all sample/demo content synthetic and client-safe.
- Preserve TNDS branding while avoiding client references and sensitive data.

## Guardrails
- No secrets, tokens, credentials, or local machine paths in committed files.
- No real client names, deal data, or private financial figures.
- Prefer deterministic examples and docs that run out of the box.

## Expected Entry Point
- `generate_presentation.py`
