---
error: true
expect:
  node_url: string
  job_id: string
  invoice_id: string
---

{"status":401,"error":"Credential required","detail":"Only the credential that paid for a job can ask the node to forget it.","job_id":"{{input.job_id}}"}
