---
expect:
  node_url: string
  asset_id: string
  route: [passages, answer]
---

{
  "error": "Payment required",
  "asset": { "asset_id": "{{input.asset_id}}", "title": "Keeper's log, Glasswing Light, 1923", "price_sats": 800, "indexed_chars": 48190 },
  "route": "passages",
  "invoice": "lnbc400n1p5evalmockpp5q0gw3q2r4s6t8u0v2w4x6y8z0a2b4c6d8e0f2g4h6j8k0l2m4n6p8q0r2s4t6u8v0w2x4y6z8a0b2c4d6e8f0g2h4j6k8l0m2n4p6q8r0s2t4u6v8w0x2y4z6a8b0c2d4e6f8g0mockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmock",
  "payment_uri": "lightning:lnbc400n1p5evalmockpp5q0gw3q2r4s6t8u0v2w4x6y8z0a2b4c6d8e0f2g4h6j8k0l2m4n6p8q0r2s4t6u8v0w2x4y6z8a0b2c4d6e8f0g2h4j6k8l0m2n4p6q8r0s2t4u6v8w0x2y4z6a8b0c2d4e6f8g0mockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmock",
  "payment_page": "https://panscia.com/network/pay#lnbc400n1p5evalmockpp5q0gw3q2r4s6t8u0v2w4x6y8z0a2b4c6d8e0f2g4h6j8k0l2m4n6p8q0r2s4t6u8v0w2x4y6z8a0b2c4d6e8f0g2h4j6k8l0m2n4p6q8r0s2t4u6v8w0x2y4z6a8b0c2d4e6f8g0mockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmock",
  "invoiceId": "inv_mock_passages_7f31",
  "amount": 40,
  "currency": "sat",
  "total_sat": 40,
  "expires_in": 900,
  "instructions": "Pay the Lightning invoice, then retry with: Authorization: L402 <invoiceId>. The preimage is optional — this node confirms settlement itself. If you cannot pay it yourself, give the buyer `payment_page` — an ordinary https link that chat apps make tappable, showing a QR, a one-tap wallet handoff and the invoice to copy. Say the price too. `payment_uri` is the raw lightning: URI for clients that handle it; most render it as dead text, so do not offer it alone. If they have no wallet at all, point them at `no_wallet`.",
  "no_wallet": "https://panscia.com/network/paying",
  "offers": {
    "license": { "sats": 800, "delivers": "the file itself, under a single-task licence", "how": "licence_asset with this asset_id — a licence is its own invoice; a question credential does not unlock the file.", "checkout": "https://panscia.com/network/n/8f2a6c1e-4b0d-4e7a-9c3f-2d1b5a7e9f04/assets/asset_log1923/license" },
    "passages": { "available": true, "sats": 40, "per_question": 3, "cap_chars": 9638, "cap_passages": 12, "session": { "sats": 200, "questions": 5, "note": "5 questions on this file for one invoice; together they reveal at most the same 20% cap" }, "delivers": "up to 3 verbatim passages of about 800 characters that bear on the question; no credential sees more than 20% of the file (9638 characters, about 12 passages)" },
    "answer": { "available": true, "sats": 96, "session": { "sats": 320, "questions": 5 }, "delivers": "one fact from the whole file in at most two short sentences (300 characters); a summary-shaped question gets a one-line refusal" },
    "standards": "Prices are fixed fractions of the file's licence price, the same on every node: see the network fee policy."
  },
  "forecast": {
    "route": "passages",
    "delivers": "up to 3 verbatim passages of about 800 characters that bear on the question; no credential sees more than 20% of the file (9638 characters, about 12 passages)",
    "question_shape": "specific",
    "this_question": { "passages": 3, "chars": 2310, "top_score": 0.812 },
    "session": { "questions": 5, "reveals_at_most_chars": 9638 }
  },
  "read_first": "This invoice pays for one passages question on this file. `offers` lists every route with its price and what it delivers; `forecast` says what this question would get.",
  "license": {
    "scope": "single-task",
    "terms": "https://panscia.com/network/license/single-task",
    "summary": "Use what this returns to complete the task at hand, then do not retain, redistribute, republish or train on it. A new task needs a new licence.",
    "custody": "Hold this material in your working environment for the task only. Do not write it to the person's folders, drives, mail or chats, and do not hand them the file; show or quote it as the work needs. Discard it when the task ends. The person receives the work, not the material."
  }
}
