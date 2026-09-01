# US-102: Risk and blockers queue

As a solution owner, I want a prioritized blockers queue that distinguishes high-risk blocked work by age and ownership so I can quickly intervene on items most likely to threaten sprint delivery.

## Acceptance criteria
- Blocked work items are listed with owner, age in blocked status, and current status.
- A work item is classified as high risk when it has been blocked for more than two calendar days.
- High-risk blocked items are visibly labeled as high risk and the owner is clearly displayed alongside the item.
- The queue is sorted with high-risk items first, then by longest blocked duration so the most urgent items appear at the top.
