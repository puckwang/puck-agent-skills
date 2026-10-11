# puck-agent-skills

[English](README.md) | 台灣中文

Puck Wang 的 Agent Skills，以 Claude Code plugin marketplace 的形式發布。

> 本專案為個人作品，並非 Anthropic 官方專案。

## 使用方式

```text
/plugin marketplace add puckwang/puck-agent-skills
/plugin install diagram-first@puck-agent-skills
```

## Plugin 列表

| Plugin | 說明 | Repo |
|---|---|---|
| `diagram-first` | 文不如圖：說明流程、架構時主動附上 ASCII 或 Mermaid(ELK)圖 | [puckwang/diagram-first-skill](https://github.com/puckwang/diagram-first-skill) |

每個 plugin 都放在獨立的 repo，並跟著該 repo 的預設分支更新；plugin 升版(`plugin.json` 的 version)後，執行 `/plugin update` 即可取得新版本。詳細說明、其他安裝方式與已知限制，請見各 repo 的 README。

## 授權

[MIT](LICENSE)
