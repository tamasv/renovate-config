# Renovate Configuration

This repository contains my personal Renovate configuration presets for automated dependency management.

## About

This configuration is based on the excellent work from [bjw-s/renovate-config](https://github.com/bjw-s/renovate-config) and incorporates best practices from multiple publicly available Renovate configurations.

## Usage

To use this configuration in your projects, extend it in your `renovate.json` file:

```json
{
  "extends": ["github>vargat/renovate-config"]
}
```

## Configuration Files

- `default.json` - Main configuration preset with recommended settings
- `automerge-github-actions.json` - Auto-merge configuration for GitHub Actions
- `automerge-docker-digest.json` - Auto-merge configuration for Docker digest updates
- `commit-message.json` - Commit message formatting rules
- `custom-managers.json5` - Custom manager configurations
- `pr-labels.json` - Pull request labeling configuration

## License

This configuration is provided as-is for public use.
