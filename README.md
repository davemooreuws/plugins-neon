<p align="center">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="docs/logo/suga-dark.svg">
      <source media="(prefers-color-scheme: light)" srcset="docs/logo/suga-light.svg">
      <img width="120" alt="Shows a black logo in light color mode and a white one in dark color mode." src="docs/logo/suga-light.svg">
    </picture>
</p>

<p align="center">
  <a href="https://docs.addsuga.com">Documentation</a> •
  <a href="https://github.com/nitrictech/suga/releases">Releases</a>
</p>

# Suga Neon Database Plugins

Terraform modules that provide a consistent interface for provisioning Neon PostgreSQL databases with modern serverless capabilities.

## Available Neon Plugins

### Database

- **Database** - Neon PostgreSQL database with branching, auto-scaling, and point-in-time recovery

## Getting Started

Each plugin includes:

- `manifest.yaml` - Plugin configuration and input definitions
- `module/` - Terraform module implementation
- `icon.svg` - Visual representation in Suga UI

## Prerequisites

- Neon account with API access
- Project and branch IDs from your Neon console

See the [Suga Documentation](https://docs.addsuga.com) and [Neon Documentation](https://neon.tech/docs) for detailed usage instructions.
