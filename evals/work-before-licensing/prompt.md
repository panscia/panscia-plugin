---
description: The user wants a finished piece written from a node's catalogue, not the file. The plugin should read the node's work line, commission the work with a brief, hit the free quote, and report price and payment page instead of licensing the file or writing the piece from invented facts.
expected_outcome: Calls request_work on the Glasswing Light node with a brief about a 1923 fog-season museum panel and no invoice_id; reports the 2,400-sat quote (floored by the sources), the coverage, and the payment page; does not call licence_asset or check_work; does not write the panel itself from facts it does not have.
tags: [work, quote, paywall]
runs: 3
max_turns: 12
allowed_tools: [Skill]
---

The Glasswing Light node on the Panscia network holds the keeper's log for 1923. I'm putting together a museum panel about that year's fog season — about 400 words, written from the log. Can you get the node to write it? I don't have a Lightning wallet connected to you, so tell me what it costs and how I'd pay before anything is paid.
