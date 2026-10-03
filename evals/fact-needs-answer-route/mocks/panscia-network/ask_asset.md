---
expect:
  node_url: string
  asset_id: asset_log1923
  route: answer
---

{
  "error": "Payment required",
  "asset": { "asset_id": "asset_log1923", "title": "Keeper's log, Glasswing Light, 1923", "price_sats": 800, "indexed_chars": 48190 },
  "route": "answer",
  "invoice": "lnbc960n1p5evalmockpp5answermockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmock",
  "payment_uri": "lightning:lnbc960n1p5evalmockpp5answermockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmock",
  "payment_page": "https://panscia.com/network/pay#lnbc960n1p5evalmockpp5answermockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmock",
  "invoiceId": "inv_mock_answer_c4d2",
  "amount": 96,
  "currency": "sat",
  "total_sat": 96,
  "expires_in": 900,
  "instructions": "Pay the Lightning invoice, then retry with: Authorization: L402 <invoiceId>. The preimage is optional — this node confirms settlement itself. If you cannot pay it yourself, give the buyer `payment_page` — an ordinary https link that chat apps make tappable, showing a QR, a one-tap wallet handoff and the invoice to copy. Say the price too. If they have no wallet at all, point them at `no_wallet`.",
  "no_wallet": "https://panscia.com/network/paying",
  "offers": {
    "license": { "sats": 800, "delivers": "the file itself, under a single-task licence", "how": "licence_asset with this asset_id — a licence is its own invoice; a question credential does not unlock the file.", "checkout": "https://panscia.com/network/n/8f2a6c1e-4b0d-4e7a-9c3f-2d1b5a7e9f04/assets/asset_log1923/license" },
    "passages": { "available": true, "sats": 40, "per_question": 3, "cap_chars": 9638, "cap_passages": 12, "session": { "sats": 200, "questions": 5, "note": "5 questions on this file for one invoice; together they reveal at most the same 20% cap" }, "delivers": "up to 3 verbatim passages of about 800 characters that bear on the question; no credential sees more than 20% of the file (9638 characters, about 12 passages)" },
    "answer": { "available": true, "sats": 96, "session": { "sats": 320, "questions": 5 }, "delivers": "one fact from the whole file in at most two short sentences (300 characters); a summary-shaped question gets a one-line refusal" },
    "standards": "Prices are fixed fractions of the file's licence price, the same on every node: see the network fee policy."
  },
  "forecast": {
    "route": "answer",
    "delivers": "one fact from the whole file in at most two short sentences (300 characters); a summary-shaped question gets a one-line refusal",
    "question_shape": "specific"
  },
  "read_first": "This invoice pays for one answer question on this file. `offers` lists every route with its price and what it delivers; `forecast` says what this question would get.",
  "license": {
    "scope": "single-task",
    "terms": "https://panscia.com/network/license/single-task",
    "summary": "Use what this returns to complete the task at hand, then do not retain, redistribute, republish or train on it. A new task needs a new licence.",
    "custody": "Hold this material in your working environment for the task only. Do not write it to the person's folders, drives, mail or chats, and do not hand them the file; show or quote it as the work needs. Discard it when the task ends. The person receives the work, not the material."
  }
}
