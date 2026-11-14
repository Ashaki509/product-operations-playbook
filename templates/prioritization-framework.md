# Prioritization Framework

A weighted scoring model for ranking roadmap candidates. It makes the reasoning behind priorities visible, so tradeoffs can be discussed with evidence.

The score is an input to the decision. Leaders still decide, and when they override the ranking, the reason is recorded.

---

## The Criteria

Score each candidate from 1 to 5 on every criterion.

| Criterion | Weight | 1 | 3 | 5 |
|-----------|--------|---|---|---|
| Strategic alignment | [30%] | No link to a current objective | Supports an objective indirectly | Directly advances a top objective |
| Customer impact | [25%] | Few customers, minor benefit | A meaningful segment, clear benefit | Most customers, or a critical need |
| Business impact | [25%] | No measurable revenue or cost effect | Moderate effect on revenue, retention, or cost | Large effect on revenue, retention, or cost |
| Confidence | [10%] | An assumption with no evidence | Some customer or usage data | Strong evidence from several sources |
| Urgency | [10%] | No time pressure | A date would be helpful | A contractual, regulatory, or competitive deadline |

The weights are placeholders. Set them with your leadership team once, then keep them fixed for the planning cycle.

---

## Effort

Size effort separately. Do not fold it into the value score.

| Size | Rough meaning | Effort points |
|------|---------------|---------------|
| S | One team, under one month | 1 |
| M | One team, about one quarter | 2 |
| L | Several teams, or more than one quarter | 4 |
| XL | A multi-quarter program | 8 |

---

## The Calculation

1. **Value score** = the sum of (score × weight) across the five criteria. The range is 1.0 to 5.0.
2. **Priority score** = value score ÷ effort points.
3. Rank by priority score, then review the ranking as a group.

---

## Scoring Sheet

| Candidate | Alignment | Customer | Business | Confidence | Urgency | Value score | Effort | Priority score | Rank |
|-----------|-----------|----------|----------|------------|---------|-------------|--------|----------------|------|
| | | | | | | | | | |
| | | | | | | | | | |
| | | | | | | | | | |

---

## Reviewing the Ranking

The score starts the conversation. Check these before you finalize:

- **Dependencies:** does a lower-ranked item unblock a higher-ranked one?
- **Balance:** does the top of the list include technical investment as well as features?
- **Capacity by team:** do the top items all land on the same team?
- **Commitments:** are contractual or compliance items covered, whatever their score?
- **Low confidence, high value:** would a small discovery effort raise confidence before a full commitment?

---

## Rules

- The same people score every candidate, using the same definitions.
- Score independently first, then discuss the differences.
- A candidate that cannot be scored needs discovery. It is not ready for the roadmap.
- When leadership overrides the ranking, record the reason in the decision log.
- Tell requesters the outcome, including when the answer is "not now."

---

## Related

- [Quarterly Planning Cadence](../cadences/quarterly-planning.md)
- [Product Review Cadence](../cadences/product-review-cadence.md)
