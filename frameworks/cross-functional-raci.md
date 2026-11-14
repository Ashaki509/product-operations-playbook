# Cross-Functional RACI

A responsibility matrix for the product lifecycle across Product, Engineering, Design, go-to-market, and Product Operations. Use it as a starting point and adjust it to how your organization is structured.

---

## Definitions

| Letter | Role | Rule |
|--------|------|------|
| **R** | Responsible | Does the work. At least one per activity. |
| **A** | Accountable | Owns the outcome and makes the final call. Exactly one per activity. |
| **C** | Consulted | Gives input before the decision. Two-way communication. |
| **I** | Informed | Told after the decision. One-way communication. |

---

## The Matrix

| Activity | Product | Engineering | Design | GTM | Product Ops | Support |
|----------|---------|-------------|--------|-----|-------------|---------|
| **Strategy and planning** | | | | | | |
| Product strategy and vision | A | C | C | C | C | I |
| Quarterly roadmap | A | R | C | C | R | I |
| OKR setting | A | R | C | C | R | I |
| Capacity and dependency planning | C | A | C | I | R | I |
| **Discovery and definition** | | | | | | |
| Customer research | A | I | R | C | C | C |
| Requirements | A | C | C | I | I | I |
| Technical design | C | A | C | I | I | I |
| Experience design | C | C | A | I | I | I |
| **Build and launch** | | | | | | |
| Development and testing | C | A | C | I | I | I |
| Launch readiness review | A | R | C | R | R | R |
| Pricing and packaging | A | I | I | R | C | I |
| Launch communications | C | I | C | A | C | I |
| Sales and support enablement | C | I | I | A | C | R |
| **Operate and learn** | | | | | | |
| Adoption and outcome tracking | A | C | C | C | R | I |
| Customer feedback synthesis | A | I | C | R | R | R |
| Post-launch review | A | R | C | R | R | C |
| Process and tooling improvement | C | C | C | C | A | I |

GTM covers Marketing, Sales, and Customer Success. Split the column if those functions have different responsibilities in your organization.

---

## How to Adapt It

1. Start with the activities where work stalls or gets done twice. Those rows matter most.
2. Review each row with the leads of every function in it.
3. Replace function names with named people for the top five activities.
4. Publish it where teams plan their work, and review it when the organization changes.

---

## Health Checks

| Check | What a problem looks like | Fix |
|-------|---------------------------|-----|
| One A per row | Two functions both believe they decide | Escalate once, record the answer, and update the matrix |
| R without A | Work happens with nobody owning the outcome | Assign an A |
| Too many Cs | Decisions wait on a long list of reviewers | Move some Cs to I |
| A column full of Rs | One function is overloaded | Rebalance or add capacity |
| A column of only Is | A function is left out until it is too late | Add a C where its input would change the decision |

---

## Related

- [Product Ops Maturity Model](product-ops-maturity-model.md)
- [Product Review Cadence](../cadences/product-review-cadence.md)
