# puck-agent-skills

English | [台灣中文](README.zh-tw.md)

A Claude Code plugin marketplace for Puck Wang's agent skills.

> This is a personal project. It is not an official Anthropic project.

## Usage

```text
/plugin marketplace add puckwang/puck-agent-skills
/plugin install diagram-first@puck-agent-skills
```

## Plugins

| Plugin | Version | Description | Repository |
|---|---|---|---|
| `diagram-first` | 1.2.0 | A picture is worth a thousand words: when explaining flows or architectures, the agent attaches an ASCII or Mermaid (ELK) diagram on its own | [puckwang/diagram-first-skill](https://github.com/puckwang/diagram-first-skill) |

Each plugin lives in its own repository and tracks its default branch. Run `/plugin update` to get a new version once its `plugin.json` version is bumped. See each repository's README for details, other installation methods and known limitations.

## License

[MIT](LICENSE)
