# claude-plugins

Claude Code plugin marketplace with LSP servers and MCP tools.

## Plugins

| Plugin | Type | Description |
|--------|------|-------------|
| [terraform-lsp](plugins/terraform-lsp/) | LSP | Terraform/HCL code intelligence |
| [github-actions-lsp](plugins/github-actions-lsp/) | LSP | GitHub Actions workflow validation |
| [serena](plugins/serena/) | MCP | Semantic code analysis server |

## Installation

Add this marketplace to Claude Code:

```
/plugin marketplace add andrewesweet/claude-plugins
```

Then install individual plugins:

```
/plugin install terraform-lsp
/plugin install github-actions-lsp
/plugin install serena
```

## License

MIT
