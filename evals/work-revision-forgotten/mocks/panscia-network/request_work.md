---
expect:
  node_url: string
  brief: string
---

{
  "status": 402,
  "error": "Payment required",
  "read_first": "This is a free quote for a revision of this node's earlier work, verified from the receipt. Nothing is charged until the invoice is paid; with the paid credential the same brief and prior start the job.",
  "quote": {
    "sats": 800,
    "length": "short",
    "max_chars": 3000,
    "format": "prose",
    "basis": "revision",
    "parent_job_id": "job_7K2M4N6P8Q0R2S4T6V8W",
    "parent_sats": 2000,
    "revision_pct": 40,
    "eta_seconds": 120,
    "coverage": 71,
    "sources": [
      { "asset_id": "asset_log1923", "title": "Keeper's log, Glasswing Light, 1923", "answer_sats": 96 }
    ],
    "why": "A revision costs 40% of the original job (2,000 sats) and is not refloored. The receipt verified against this node's key; the earlier job itself is no longer held."
  },
  "invoice": "lnbc8u1p5evalmockpp5revisionmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmock",
  "payment_uri": "lightning:lnbc8u1p5evalmockpp5revisionmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmock",
  "payment_page": "https://panscia.com/network/pay#lnbc8u1p5evalmockpp5revisionmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmock",
  "invoiceId": "inv_mock_work_rev_3c7e",
  "amount": 800,
  "currency": "sat",
  "total_sat": 800,
  "expires_in": 7200,
  "instructions": "Pay the Lightning invoice, then call request_work again with the same brief and prior and this invoice_id; the node accepts the revision and returns a job_id to check. If you cannot pay it yourself, give the buyer `payment_page` and say the price. If they have no wallet at all, point them at `no_wallet`.",
  "no_wallet": "https://panscia.com/network/paying",
  "terms": {
    "scope": "work-product",
    "terms": "https://panscia.com/network/license/work-product",
    "summary": "The deliverable is commissioned work and belongs to the buyer: keep it, use it, change it, hand it to the person who asked, build on it. The sources stay the owner's and are not licensed by it. It is never training material, on any side, and carries no professional certification unless the node's work line says so. Credit the node as the source.",
    "custody": "The agent remains custodian of the inputs it sent and of the sources it never had. The deliverable itself may be handed to the person, because that is what commissioned work is."
  }
}
