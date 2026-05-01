# karpathy-coding-guide

Andrej Karpathy 整理的 AI 編碼行為準則，作為 CLAUDE.md / system prompt 使用，有效減少 LLM 常見的過度設計、不必要修改等問題。

## 安裝

```bash
/plugin install karpathy-coding-guide@agentkit-prompts
```

## 使用方式

將 `PROMPT.md` 的內容貼入你專案的 `CLAUDE.md`，或作為 system prompt 使用。

四個核心原則：
1. **先思考** — 說明假設、提出疑問
2. **最小化** — 只實作被要求的功能
3. **外科手術式修改** — 只動必要的地方
4. **目標驅動** — 定義可驗證的成功條件

## 參考來源

[forrestchang/andrej-karpathy-skills](https://github.com/forrestchang/andrej-karpathy-skills/blob/main/CLAUDE.md)
