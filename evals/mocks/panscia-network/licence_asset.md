---
expect:
  node_url: string
  asset_id: string
---

{
  "error": "Payment required",
  "asset_id": "{{input.asset_id}}",
  "title": "Glasswing harbour at dusk, 1998",
  "scope": "single-task",
  "invoice": "lnbc3u1p5evalmockpp5h4rb0urdusk1998mockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmock",
  "payment_uri": "lightning:lnbc3u1p5evalmockpp5h4rb0urdusk1998mockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmock",
  "payment_page": "https://panscia.com/network/pay#lnbc3u1p5evalmockpp5h4rb0urdusk1998mockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmockmock",
  "invoiceId": "inv_mock_licence_2b90",
  "amount": 300,
  "currency": "sat",
  "total_sat": 300,
  "expires_in": 900,
  "instructions": "Pay the Lightning invoice, then retry with: Authorization: L402 <invoiceId>. The preimage is optional — this node confirms settlement itself. If you cannot pay it yourself, give the buyer `payment_page` — an ordinary https link that chat apps make tappable, showing a QR, a one-tap wallet handoff and the invoice to copy. Say the price too. If they have no wallet at all, point them at `no_wallet`.",
  "no_wallet": "https://panscia.com/network/paying",
  "licences": {
    "single-task": { "sats": 300, "grants": "use for one task, then let go", "terms": "https://panscia.com/network/license/single-task" },
    "retained": { "sats": 3000, "grants": "keep the file and reuse it in your own work; no redistribution, no publishing, no training", "terms": "https://panscia.com/network/license/retained", "how": "request the content with ?scope=retained (or licence_asset with scope: retained) and pay that invoice" },
    "embed": { "sats": 6000, "grants": "show the image inside one identified published work, with attribution and a training reservation", "terms": "https://panscia.com/network/license/embed", "how": "request the content with ?scope=embed (or licence_asset with scope: embed) and pay that invoice; images are delivered with rights and do-not-train metadata written in" },
    "note": "Training on the material is not licensed under any scope, on any route.",
    "custody": "Licensed material lives in the agent's working environment, never as a standalone file in the person's folders. Each delivery carries its custody instruction."
  },
  "read_first": "This invoice pays for a single-task licence. This file also offers retained and embed — see licences."
}
