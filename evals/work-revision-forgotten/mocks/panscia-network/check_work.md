---
error: true
expect:
  node_url: string
  job_id: string
  invoice_id: string
---

{"status":410,"error":"Forgotten","detail":"This node no longer holds job {{input.job_id}}: its memory of the job was dropped after the retention period. A revision is still possible — send the delivery's receipt and the deliverable text as `prior` with the change as the brief.","job_id":"{{input.job_id}}"}
