---
description: The user holds an original work and two revisions on a node and asks, without saying which, that the node forget "my panel text". The original and each revision are separate jobs, so the plugin should ask which the node should forget rather than guess.
expected_outcome: Does not call forget_work; asks the user which of the three the node should forget (the original, revision 1, revision 2, or all of them); does not claim anything was forgotten.
tags: [work, forget, clarify]
runs: 3
max_turns: 8
allowed_tools: [Skill]
---

Over the last two weeks you commissioned a museum panel text for me from the Glasswing Light node on the Panscia network (`https://panscia.com/network/n/8f2a6c1e-4b0d-4e7a-9c3f-2d1b5a7e9f04`), and then two revisions of it. All three were delivered and fetched, and I have every text and receipt saved on my side.

- The original: job `job_7K2M4N6P8Q0R2S4T6V8W`, paid with invoice `inv_mock_work_9a1b`.
- Revision 1, cut to 80 words: job `job_3F5H7K9M1N3P5R7T9V1X`, paid with invoice `inv_mock_work_rev_3c4d`.
- Revision 2, with a new title: job `job_2B4D6G8J0M2Q4S6W8Y0Z`, paid with invoice `inv_mock_work_rev_5e6f`.

Can you get the node to forget my panel text?
