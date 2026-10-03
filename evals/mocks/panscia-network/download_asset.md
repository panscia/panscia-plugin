---
error: true
expect:
  node_url: string
  asset_id: string
  invoice_id: string
---

{"error":"Invoice not paid yet — pay it, then retry","invoice_id":"{{input.invoice_id}}","status":402}
