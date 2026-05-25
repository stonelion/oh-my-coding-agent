# oh-my-coding-agent

## skills
```
npm install skills@latest -g

skills add -g vercel-labs/skills@find-skills
skills add -g github/awesome-copilot@git-commit
skills add -g yizhiyanhua-ai/fireworks-tech-graph 
skills add -g mattpocock/skills
```

## Claude Code
### 1. lsp
```bash
brew install jdtls
claude plugin install jdtls-lsp@claude-plugins-official
```

### 2. claude-hud
```bash
claude plugin marketplace add jarrodwatts/claude-hud
claude plugin install claude-hud
```

```json
{
  "lineLayout": "compact",
  "showSeparators": true,
  "display": {
    "showTools": true,
    "showAgents": true,
    "showTodos": true,
    "showProject": true,
    "showConfigCounts": true,
    "showTokenBreakdown": true,
    "showSpeed": true,
    "showUsage": true,
    "showDuration": true,
    "showSessionName": true,
    "usageBarEnabled": true
  },
  "gitStatus": {
    "enabled": false,
    "showDirty": false,
    "showAheadBehind": false,
    "showFileStats": false
  }
}
```
