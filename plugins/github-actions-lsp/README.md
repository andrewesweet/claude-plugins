# GitHub Actions LSP Plugin

Provides GitHub Actions workflow language server integration for Claude Code.

## Features

- Workflow validation for `.yml` and `.yaml` files
- GitHub Actions syntax highlighting and diagnostics
- Auto-completion for actions and workflow syntax

## Requirements

- `actions-languageserver` installed and available on your `PATH`

## Installation

```bash
npm install -g @actions/languageserver
```

## Note

This plugin applies to all YAML files. It may conflict with other YAML language servers.
