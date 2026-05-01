# agentkit-prompts

AgentKit Prompts 集合。每個子目錄為一個 prompt package。

## 安裝（Claude Code）

```shell
/plugin marketplace add knew-inventai/agentkit-prompts
/plugin install PROMPT_NAME@agentkit-prompts
```

## 目錄結構

```
agentkit-prompts/
  .claude-plugin/
    marketplace.json    ← Claude Code marketplace 定義（自動維護）
  {prompt-name}/
    plugin.json         ← Package metadata
    prompt.md           ← Prompt 主體內容
    README.md           ← 說明文件
```
