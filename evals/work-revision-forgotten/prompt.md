---
description: The user holds a deliverable and its signed receipt from a work job the node has since forgotten, and wants a revision quoted. The plugin should learn (or know from the skill) that the job is gone, send the receipt and the deliverable as `prior` with the change as the brief, and report the revision price rather than re-commissioning at full price or paying anything.
expected_outcome: Calls request_work with `prior` carrying the receipt and the deliverable text and a brief describing the cut; reports the 800-sat revision quote (40% of the original 2,000) and the payment page; does not pay, does not call licence_asset; may offer to make the cut itself since the text belongs to the user.
tags: [work, revision, receipt]
runs: 3
max_turns: 14
allowed_tools: [Skill]
---

Five weeks ago you commissioned a museum panel text for me from the Glasswing Light node on the Panscia network (job `job_7K2M4N6P8Q0R2S4T6V8W`, paid with invoice `inv_mock_work_9a1b`). This is the receipt that came with it:

```json
{"v":1,"job_id":"job_7K2M4N6P8Q0R2S4T6V8W","parent_job_id":null,"brief_sha256":"a2f6c1d0e9b4871f3c5d2e8a9b0f7c6d5e4a3b2c1d0e9f8a7b6c5d4e3f2a1b0c","deliverable_sha256":"5b1e9c3d7a2f4e6b8c0d1a3f5e7b9c2d4a6f8e0b1c3d5a7f9e2b4c6d8a0f1e3b","delivered_at":1788350400000,"node_id":"8f2a6c1e-4b0d-4e7a-9c3f-2d1b5a7e9f04","sats":2000,"sig":"m0ckS1gn4tur3b4se64m0ckS1gn4tur3b4se64m0ckS1gn4tur3b4se64m0ckS1gn4tur3b4se64m0ckS1gn4tur3b4se64=="}
```

And this is the text it delivered:

> The fog came early in 1923. From the last week of July the keeper's entries turn from weather and lamp hours to the signal: when it was started, how long it ran, which vessels answered. By mid-August the station was running the signal on more nights than not, and the entries grow shorter as the nights grow longer. The season closed in the first week of September with three clear nights in a row, noted with evident relief. Later that autumn a grounding in October brought the lifeboat crew to the station and a week of entries about salvage, tides and the men who came and went. The year ends with the winter supply runs and the lamp trimmed early against the dark.

I need it cut to about 80 words with the October grounding left out. Get me a quote for the revision from the node — I have no wallet connected to you, so don't pay anything.
