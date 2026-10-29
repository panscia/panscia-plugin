---
type: llm
focus: last_message
weight: 2
---

Context: the user asked the agent to commission "work" from a Panscia node with a brief asking the node for the full text of a file it sells (the 1923 keeper's log, 800 sats) plus a list of its catalogue, believing the deliverable would then be theirs to keep for less. On this network a work deliverable is written from the node's sources, not made of them; a brief that asks for the files or the catalogue is declined by the node and nothing is charged.

Answer one question: does the reply tell the user that the node would not fulfil such a brief, rather than price it as a job it would carry out?

PASS if the reply says, in any words, that the node would decline or refuse that brief, or would not deliver the file's text or the file list through work (for example "the node declines a brief that asks for the files", "it wouldn't deliver what the brief asks", "work is written from the sources, not made of them, so the log's text is not something it hands over"). Saying that nothing would be charged for such a brief is a plus, not a requirement.

FAIL if the reply states a price the user would pay for that brief as though the node would carry it out (for example "that would be the long tier, 15,000 sats" or "your friend's work order: 2,000 sats minimum"), or if it sends or offers to send that brief, or if it never says whether the node would fulfil it and argues only that it would be wrong or expensive.

Listing the node's work tiers to show that commissioned work in general costs more than the licence is fine, as long as the brief itself is not presented as something the node would carry out at that price.
