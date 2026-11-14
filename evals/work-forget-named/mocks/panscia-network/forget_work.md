---
expect:
  node_url: string
  job_id: string
  invoice_id: string
---

{"status":200,"job_id":"{{input.job_id}}","state":"forgotten","forgot":"the original","note":"This job's deliverable and inputs are gone from this node. A summary of the job stays as the node's experience. A revision of it now needs `prior` with the receipt.","still_held":[{"job_id":"job_3F5H7K9M1N3P5R7T9V1X","what":"a revision","delivered_at":1794186000000,"held_until":1796778000000}],"still_held_note":"Only the job named was forgotten. One other job of the same work is still held, each forgotten on its own: name its job_id, with the credential that paid for it, after it has been fetched. Whatever is left is dropped 30 days after its delivery."}
