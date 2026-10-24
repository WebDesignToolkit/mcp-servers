# MCP server review checklist

- Identity: official repository, maintained publisher, license and changelog.
- Transport: stdio or network; bind network access to least privilege.
- Tools: list every action and distinguish reads from writes and destructive operations.
- Secrets: environment variables, token scope, logs, rotation and no accidental exposure.
- Filesystem: allowed roots, symlink escapes, arbitrary code execution risks.
- Browser: permission prompts, domain boundaries, SSRF and injection defense.
- Reproducible smoke test: execute only in a constrained authorized environment.
- Document unsupported assumptions and do not call a candidate "verified" without evidence.
