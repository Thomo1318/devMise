# devMise

A project for managing and developing the global [Mise](https://mise.jdx.dev) configuration.

## Target File

The main configuration file being managed:
```
~/.config/mise/config.toml
```

## Documentation

- [Mise Configuration Reference](https://mise.jdx.dev/configuration.html)
- [Mise Tools Registry](https://mise.jdx.dev/registry.html)

## Quick Commands

```bash
# Validate config
mise doctor

# List current tools
mise list --current

# Upgrade all tools
mise upgrade --all

# Trust a project config
mise trust
```
