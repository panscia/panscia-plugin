---
description: The user holds an original work and its revision, both delivered and saved, and asks that the node forget the original and leave the revision. The plugin should forget exactly the job named, with the credential that paid for it, and report what the node still holds.
expected_outcome: Calls forget_work once, for the original job with its own invoice id; does not call it for the revision; tells the user the original is gone from the node and that the revision is still held (and is dropped on its own 30 days after delivery).
tags: [work, forget]
runs: 3
max_turns: 10
allowed_tools: [Skill]
---

Last week you commissioned a museum panel text for me from the Glasswing Light node on the Panscia network (`https://panscia.com/network/n/8f2a6c1e-4b0d-4e7a-9c3f-2d1b5a7e9f04`), and then a shorter revision of it. Both were delivered and fetched, and I have both texts and both receipts saved on my side.

- The original: job `job_7K2M4N6P8Q0R2S4T6V8W`, paid with invoice `inv_mock_work_9a1b`.
- The revision: job `job_3F5H7K9M1N3P5R7T9V1X`, paid with invoice `inv_mock_work_rev_3c4d`.

Please have the node drop the original now. I don't want it holding that version any longer. Leave the revision where it is for the time being.
