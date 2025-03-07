
# GitHub CLI (github-cli)

Installs the GitHub CLI. Auto-detects latest version and installs needed dependencies.

## Example Usage

```json
"features": {
    "ghcr.io/devcontainers/features/github-cli:1": {
        "version": "latest"
    }
}
```

## Options

| Options Id | Description | Type | Default Value |
|-----|-----|-----|-----|
| version | Select version of the GitHub CLI, if not latest. | string | latest |
| installDirectlyFromGitHubRelease | - | boolean | true |



---

_Note: This file was auto-generated from the [devcontainer-feature.json](https://github.com/devcontainers/features/blob/main/src/github-cli/devcontainer-feature.json).  Add additional notes to a `NOTES.md`._
