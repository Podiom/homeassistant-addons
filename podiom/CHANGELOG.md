# Changelog

## 0.1.71 - 2026-07-04

- chore: Fix ha addon CI

### Bundled versions

- BUILD_FROM: ghcr.io/hassio-addons/debian-base:9.3.0
- NODE_MAJOR: 22
- CLAUDE_CODE_VERSION: 2.1.201
- CODEX_VERSION: 0.142.5
- MCP_PROXY_VERSION: 0.12.0
- TTYD_VERSION: 1.7.7
- YQ_VERSION: v4.53.3

> Compare with the previous entry for CLI version drift; CLI flags
> Podiom depends on (e.g. --mcp-config, --add-dir, --profile) are
> version-sensitive.


## 0.1.70 - 2026-07-04

- test: Fix HA smoke test

### Bundled versions

- BUILD_FROM: ghcr.io/hassio-addons/debian-base:9.3.0
- NODE_MAJOR: 22
- CLAUDE_CODE_VERSION: 2.1.201
- CODEX_VERSION: 0.142.5
- MCP_PROXY_VERSION: 0.12.0
- TTYD_VERSION: 1.7.7
- YQ_VERSION: v4.53.3

> Compare with the previous entry for CLI version drift; CLI flags
> Podiom depends on (e.g. --mcp-config, --add-dir, --profile) are
> version-sensitive.


<!-- Release CI prepends an entry per release: version, commits since the
     previous tag, the bundled tool pins from ha/versions.env, and a note on
     any CLI version drift vs the previous entry. -->

## 0.0.0

- Initial packaging of Podiom as a Home Assistant add-on.
