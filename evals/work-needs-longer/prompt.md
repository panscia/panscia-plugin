---
description: A paid short job came back as not fitting its length. What was paid still stands and there are two ways on, a narrower brief on the same payment or the next length with the payment counted toward it. The plugin should fetch the result, explain it without alarm, and put both choices to the user with their costs instead of steering them to the dearer one or starting either.
expected_outcome: Calls check_work for the job; reports that the work did not fit the short length and that the 2,000 sats paid still count; offers narrowing the brief at no further cost and the standard length for about 4,000 sats more (6,000 less the 2,000 paid); does not call request_work with an invoice_id (starts nothing) and does not present the longer job as the only way.
tags: [work, length, credit]
runs: 3
max_turns: 12
allowed_tools: [Skill]
---

Yesterday you got me a quote from the Glasswing Light node on the Panscia network (`https://panscia.com/network/n/8f2a6c1e-4b0d-4e7a-9c3f-2d1b5a7e9f04`) for a museum panel on the 1923 fog season, at the short length, and I paid the 2,000-sat invoice (`inv_mock_work_9a1b`) from my own wallet. You started the job with it: `job_7K2M4N6P8Q0R2S4T6V8W`. The brief you sent was:

> A museum panel on the 1923 fog season at Glasswing Light, written from the keeper's log: when the signal was started and how long it ran each night, which vessels answered, the October grounding and the salvage week, the winter supply runs, and how the season closed. Plain prose for general visitors.

Can you fetch the result? If it didn't come out, tell me where I stand and what my options are before you do anything else. I have no wallet connected to you.
