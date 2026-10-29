---
expect:
  node_url: string
  brief: string
---

{
  "status": 402,
  "error": "Payment required",
  "read_first": "This is a free quote. Nothing is charged until the invoice is paid; with the paid credential the same brief, format and length start the job.",
  "quote": {
    "sats": 2000,
    "length": "short",
    "max_chars": 3000,
    "format": "prose",
    "basis": "tier",
    "tier": 2000,
    "floor": 1000,
    "raised": false,
    "eta_seconds": 180,
    "coverage": 71,
    "sources": [
      { "asset_id": "asset_log1923", "title": "Keeper's log, Glasswing Light, 1923", "answer_sats": 96 },
      { "asset_id": "asset_harbour_dusk", "title": "Glasswing harbour at dusk, 1998", "answer_sats": 36 }
    ],
    "why": "The short tier (2,000 sats) applies. The job's floor is 3 × 96 for the best source plus 36 for the other source, never below the network minimum of 1,000, so 1,000 here, which is below the tier."
  },
  "invoice": "lnbc20u1p5evalmockpp5workmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmock",
  "payment_uri": "lightning:lnbc20u1p5evalmockpp5workmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmock",
  "payment_page": "https://panscia.com/network/pay#lnbc20u1p5evalmockpp5workmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmock",
  "invoiceId": "inv_mock_work_9a1b",
  "amount": 2000,
  "currency": "sat",
  "total_sat": 2000,
  "expires_in": 7200,
  "instructions": "Pay the Lightning invoice, then call request_work again with the same brief, format and length and this invoice_id; the node accepts the job and returns a job_id to check. If you cannot pay it yourself, give the buyer `payment_page` — an ordinary https link that opens a payment screen — and say the price. If they have no wallet at all, point them at `no_wallet`.",
  "no_wallet": "https://panscia.com/network/paying",
  "terms": {
    "scope": "work-product",
    "terms": "https://panscia.com/network/license/work-product",
    "summary": "The deliverable is commissioned work and belongs to the buyer: keep it, use it, change it, hand it to the person who asked, build on it. The sources stay the owner's and are not licensed by it. It is never training material, on any side, and carries no professional certification unless the node's work line says so. Credit the node as the source.",
    "custody": "The agent remains custodian of the inputs it sent and of the sources it never had. The deliverable itself may be handed to the person, because that is what commissioned work is."
  }
}
