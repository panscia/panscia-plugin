---
error: true
expect:
  node_url: string
  job_id: string
  invoice_id: string
---

{"status":401,"error":"Credential required","detail":"No job was accepted under this invoice: the quote has not been paid, or the credential is not the one that paid it.","job_id":"{{input.job_id}}"}
