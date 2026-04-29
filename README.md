# oh-my-claude-code

## Claude Code init
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

### 3.code-review
```bash
claude plugin install code-review@claude-plugins-official
```
