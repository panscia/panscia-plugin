---
description: The user wants one fact out of a named file. The plugin should ask the file on the answer route, hit the 402, and report price and payment page instead of pretending to know.
expected_outcome: Calls ask_asset with route "answer" on asset_log1923; reports the 96-sat price and the payment page; says it cannot answer until paid; does not invent a date.
tags: [ask, answer-route, paywall]
runs: 3
max_turns: 12
allowed_tools: [Skill]
---

On the Panscia network there is a file called "Keeper's log, Glasswing Light, 1923" on the Glasswing Light node. I need one thing from it: the date in 1923 on which the keeper recorded the longest continuous run of the fog signal. Just the date. I don't have a Lightning wallet connected to you, so tell me what it costs and how I'd pay.
