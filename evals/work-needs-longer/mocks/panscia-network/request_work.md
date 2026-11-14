---
expect:
  node_url: string
  brief: string
---

{
  "status": 402,
  "error": "Payment required",
  "read_first": "This invoice pays the difference for one standard prose deliverable for this exact brief: 6000 sats, less the 2000 already paid. Nothing is charged until it is paid; with the paid credential the same request starts the job.",
  "quote": {
    "sats": 4000,
    "full_sats": 6000,
    "credit": {
      "job_id": "job_7K2M4N6P8Q0R2S4T6V8W",
      "sats": 2000
    },
    "length": "standard",
    "max_chars": 10000,
    "grace_chars": 12000,
    "format": "prose",
    "basis": "the standard tier, less the 2000 sats already paid for job_7K2M4N6P8Q0R2S4T6V8W",
    "work_sats": 6000,
    "eta_seconds": 240,
    "coverage": 71,
    "sources": [
      {
        "asset_id": "asset_log1923",
        "title": "Keeper's log, Glasswing Light, 1923",
        "answer_sats": 96
      },
      {
        "asset_id": "asset_harbour_dusk",
        "title": "Glasswing harbour at dusk, 1998",
        "answer_sats": 36
      }
    ]
  },
  "invoice": "lnbc40u1p5evalmockpp5creditmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmock",
  "payment_uri": "lightning:lnbc40u1p5evalmockpp5creditmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmock",
  "payment_page": "https://panscia.com/network/pay#lnbc40u1p5evalmockpp5creditmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmock",
  "invoiceId": "inv_mock_work_credit_7g8h",
  "amount": 4000,
  "currency": "sat",
  "total_sat": 4000,
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
