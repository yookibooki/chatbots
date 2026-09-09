# Hard Requirements
- autoscale: fits viewport, no scroll, scales both; refit on load/resize/mutations
- square: cards square, size recalc on resize/add/remove
- gap: identical both, CSS clamp w/ padding, unaffected by content/logo
- logo: contain, centered both, scales w/ card, no overflow/stretch, doesn't size card, inset clears badges
- badges: score chip top-left, model chip bottom-right, absolute, above logo, never affects layout
- dynamic: add/remove auto-fits, no hardcoded count/cols, all sizes from live styles
- coverage: try all col counts, max card size, ties→more cols, centered noscroll
- ordering: descending score, keep on any edit
- style: #121212 body, #1e1e1e cards, r16, glass chips white text
- stack: single vanilla index.html, no framework/build, only icons/* external

# Mapping
chatgpt.com:GPT-5.6 Luna,claude.ai:Claude Sonnet 5,meta.ai:Muse Spark 1.3,chat.together.ai:Kimi K3,kimi.ai:K2.6,chat.z.ai:GLM-5.3,gemini.google.com:Gemini 3.6 Flash,chat.qwen.ai:Qwen3.8 Max,aistudio.tencent.ai:Hy4 preview,chat.deepseek.com:DeepSeek V4 Pro 0813,chat.motiftech.io:Motif 3,agent.minimax.io:MiniMax-M3
