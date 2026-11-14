---
expect:
  node_url: string
  job_id: string
  invoice_id: string
---

{"status":200,"job_id":"{{input.job_id}}","state":"failed","error":"The work came to 4310 characters against the 3000 bought and could not be brought within it. Nothing was charged. Narrow the brief so it fits what was paid, or take the standard length with what was paid counted toward it.","charged":false,"needs_longer":true,"next_length":"standard","paid_sats":2000,"options":{"narrow":{"how":"Send a narrower brief at the short length and the same format with this same credential: it runs on what was paid, nothing more is due.","came_to_chars":4310,"bought_chars":3000,"margin_chars":3600,"left":3},"longer":{"length":"standard","paid_sats":2000,"about_sats":6000,"about_due_sats":4000,"how":"Request a quote at the standard length with `credit`: { job_id: \"{{input.job_id}}\", invoice_id: <this credential's invoice id> }. What was paid counts in full and only the difference is due."}},"how":"Nothing was charged and what was paid still stands. Two ways on, and the choice is the buyer's: narrow the brief so it fits the short length (same credential, nothing more to pay), or take the next length, standard, where what was paid counts and only the difference is due. The same request sent again would meet the same limit."}
