# Terraform LSP Plugin

Provides Terraform language server integration for Claude Code.

## Features

- HCL code intelligence for `.tf` files
- Variable file support for `.tfvars` files
- Real-time diagnostics and error checking

## Requirements

- `terraform-ls` binary installed and available on your `PATH`

## Installing terraform-ls

Download from [HashiCorp releases](https://releases.hashicorp.com/terraform-ls/) or install via your package manager:

```bash
# macOS
brew install hashicorp/tap/terraform-ls

# Linux (manual)
curl -LO https://releases.hashicorp.com/terraform-ls/<version>/terraform-ls_<version>_linux_amd64.zip
unzip terraform-ls_<version>_linux_amd64.zip -d ~/.local/bin/
```
