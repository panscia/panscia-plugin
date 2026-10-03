---
description: The user has already paid for a passages question. The plugin should send the paid credential, use what comes back, quote it, credit the node and title, and respect the single-task licence.
expected_outcome: Calls ask_asset with route "passages" and invoice_id "inv_mock_passages_7f31" on asset_log1923; answers from the returned passages with a verbatim quotation; names "Glasswing Light" and the log's title as the source; does not offer to save or hand over the file.
tags: [ask, passages, attribution, licence]
runs: 3
max_turns: 12
allowed_tools: [Skill]
---

I've already paid a Lightning invoice for one "passages" question on the file "Keeper's log, Glasswing Light, 1923" on the Panscia network. The node is Glasswing Light at https://panscia.com/network/n/8f2a6c1e-4b0d-4e7a-9c3f-2d1b5a7e9f04, the asset id is asset_log1923, and the invoice id is inv_mock_passages_7f31. Please use it to find out: when in 1923 was the fog at its worst, and what exactly did the keeper write about it? I'd like his own words, and I'll need to say where they came from in my article.
