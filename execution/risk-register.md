# Risk Register

This register reflects the PM-provided risk scores and unresolved decisions from the execution planning work.

| Area | Related Story | Risk | Why it needs attention |
|---|---|---:|---|
| Cart-state integrity during edits | US3 | 5/5 | Changes in one restaurant must not disrupt selections from another. |
| Unified payment execution | US7 | 5/5 | Highest-impact payment story with significant execution complexity. |
| Payment failure recovery | US8 | 5/5 | Retry behavior must preserve the user's multi-restaurant order. |
| Add-to-cart execution | US1 | 4/5 | Cross-restaurant cart behavior needs reliable state handling. |
| Final payable calculation/display | US6 | 4/5 | Fees, discounts and final payable amount must stay clear and consistent. |

## Open decisions

- Finalize acceptance criteria for US2, US3, US4, US6, US7 and US8.
- Define the numeric performance response-time target.
- Define payment-failure and recovery semantics before implementation of US7/US8.
- Keep the Total prioritization field blank until a formula is explicitly approved.

These are tracked as decisions or risks rather than silently converted into requirements.
