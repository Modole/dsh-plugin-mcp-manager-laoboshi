# MCP 管理 · 劳博士 DSH 插件

在 DSH Web 中管理 stdio 与 Streamable HTTP MCP Server。

## 安装

```bash
dsh plugin --profile web add https://github.com/Modole/dsh-plugin-mcp-manager-laoboshi.git
```

安装后重启 `dsh web`。DSH 会读取 `dsh.bundle` manifest，并自动把本插件加入当前 profile。

## 来源与作者

本插件从 [劳博士 Agent Studio](https://github.com/Modole/laobos-agent-studio) 的内置能力独立整理而来。作者：Modole。

## 安全

插件代码以当前用户权限运行。安装前请审阅源码；不要把密钥、SSH 私钥或本机运行数据库提交到 Issue。

## 许可证

MIT
