# MCP 管理 · Laoboshi DSH Plugin

在 DSH Web 中管理 stdio 与 Streamable HTTP MCP Server。

## Install

```bash
dsh plugin --profile web add https://github.com/Modole/dsh-plugin-mcp-manager-laoboshi.git
```

Restart `dsh web` after installation. DSH reads the `dsh.bundle` manifest and adds this package to the selected profile.

## Origin and author

Extracted from the built-in capability in [Laoboshi Agent Studio](https://github.com/Modole/laobos-agent-studio). Author: Modole.

## Security

Plugins execute with the current user's permissions. Review the source before installation and never post credentials, SSH private keys, or local runtime databases in issues.

## License

MIT
