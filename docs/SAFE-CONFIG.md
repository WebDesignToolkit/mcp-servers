# Safe configuration principles

Prefer scoped credentials and explicit allowed directories. Pin the package version only after reviewing the official documentation. Example values such as YOUR_TOKEN_HERE are placeholders, not secrets.

Do not blindly paste an unreviewed package launcher into your main agent configuration. Begin in a local test environment, inspect tool descriptions and permissions, and require confirmation for writes and external actions.
