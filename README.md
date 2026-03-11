# Vulnerable Static Analysis Lab Repo

This repository is intentionally vulnerable and is designed for teaching static analysis, GitHub Code Scanning, and Dependabot.

## Intended learning goals
- Distinguish source-code static analysis from dependency analysis
- Inspect findings in GitHub Code Scanning
- Inspect dependency findings / pull requests from Dependabot
- Fix a code-level vulnerability and a dependency-level vulnerability

## Deliberately seeded issues
- SQL injection
- Path traversal
- Hardcoded secret
- Weak token generation
- Outdated dependencies

## Run locally (optional)
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python app.py
