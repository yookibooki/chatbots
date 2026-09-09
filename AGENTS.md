# Pass Criteria

| crit | requirement | pass when |
|---|---|---|
| autoscale | grid adapts to viewport | all cards visible at any viewport size, zero scroll h or v, updates live on resize |
| square | cards square | aspect 1:1 (±1px) at all times, incl. immediately after add/remove/resize |
| gap | uniform spacing | every measured gap h and v identical; content/logo never alters spacing |
| logo | contained logos | proportional, fully visible, centered both axes, never sizes card, stays clear of badges |
| badges | chips per card | score top-left, model bottom-right, above logo, zero layout impact |
| dynamic | count-agnostic | add/remove refits with no reload; code has no hardcoded counts/cols |
| coverage | max area use | no column count yields a larger card (small tolerance), grid stays centered |
| ordering | score sort | data-score non-increasing down the list after any edit |
| style | visual baseline | dark theme, rounded cards, glass chips w/ white text, as in current file |
| stack | zero-dep vanilla | single self-contained index.html, no framework/build/CDN, icons/* only external |

# Mapping

| website | best model |
|---|---|
| chatgpt.com | GPT-5.6 Luna |
| claude.ai | Claude Sonnet 5 |
| meta.ai | Muse Spark 1.3 |
| chat.together.ai | Kimi K3 |
| kimi.ai | K2.6 |
| chat.z.ai | GLM-5.3 |
| gemini.google.com | Gemini 3.6 Flash |
| chat.qwen.ai | Qwen3.8 Max |
| aistudio.tencent.ai | Hy4 preview |
| chat.deepseek.com | DeepSeek V4 Pro 0813 |
| chat.motiftech.io | Motif 3 |
| agent.minimax.io | MiniMax-M3 |
