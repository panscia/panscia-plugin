---
expect:
  node_url: string
  asset_id: asset_log1923
  route: passages
---

{
  "route": "passages",
  "asset": { "asset_id": "asset_log1923", "title": "Keeper's log, Glasswing Light, 1923", "price_sats": 800, "indexed_chars": 48190 },
  "question": "{{input.question}}",
  "passages": [
    {
      "chunk_id": "asset_log1923:c0211",
      "score": 0.8419,
      "text": "Aug 9. Fog thick from before dawn, the thickest of the year so far, could not see the slip from the gallery. Signal run from 4.50 am without a stop. Lamp kept lit through the day. Tide at the slip 10 ft 4 in at high water, sea quiet under the fog. No vessels seen; heard the Ellen Marr's horn to the south about noon and answered her. Oil 31 gal.\nAug 10. Fog continues, no break. Signal still running, Walter spelled me at the engine from 2 am to 6. Could not get the dory out for the mail. Lamp lit all day again. Oil 29 gal, will need the tender if this holds."
    },
    {
      "chunk_id": "asset_log1923:c0212",
      "score": 0.8033,
      "text": "Aug 11. Fog lifted 3.20 pm after sixty-two hours and a half on the signal, the longest run I have had to log at this station. Cleared to a fine evening, wind SW light. Shut the signal down at 3.25 pm and let the engine cool. Walter went for the mail in the dory. Two schooners outbound at dusk, one the Ellen Marr. Oil 27 gal. Wrote the tender for oil by the mail."
    },
    {
      "chunk_id": "asset_log1923:c0198",
      "score": 0.6127,
      "text": "Jul 28. Fog in by 6 pm, signal started 6.10 pm, run until 9.40 next morning. First real fog of the season. Lamp lit 7.05 pm. Tide at the slip 9 ft 8 in at high water. Oil 36 gal."
    }
  ],
  "allowance": {
    "cap_chars": 9638,
    "used_chars": 1247,
    "remaining_chars": 8391,
    "note": "Pass the chunk_id values above as exclude_chunk_ids on a follow-up so it reaches new material."
  },
  "license_offer": {
    "how": "licence_asset with this asset_id — a licence is its own invoice; a question credential does not unlock the file.",
    "checkout": "https://panscia.com/network/n/8f2a6c1e-4b0d-4e7a-9c3f-2d1b5a7e9f04/assets/asset_log1923/license",
    "sats": 800
  },
  "pass": null,
  "sats_paid": 40,
  "node_id": "8f2a6c1e-4b0d-4e7a-9c3f-2d1b5a7e9f04",
  "license": {
    "scope": "single-task",
    "terms": "https://panscia.com/network/license/single-task",
    "summary": "Use what this returns to complete the task at hand, then do not retain, redistribute, republish or train on it. A new task needs a new licence.",
    "custody": "Hold this material in your working environment for the task only. Do not write it to the person's folders, drives, mail or chats, and do not hand them the file; show or quote it as the work needs. Discard it when the task ends. The person receives the work, not the material."
  }
}
