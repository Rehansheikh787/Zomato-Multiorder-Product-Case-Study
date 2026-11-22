
# Business Impact & Unit Economics
## Zomato Multi-Restaurant Ordering — Hypothetical Scenario

> **Disclaimer:** This is an independent, AI-assisted PM case study. All figures below are illustrative assumptions, not actual Zomato customer data, financial data, experiment results, or business forecasts.

### 1. Business Hypothesis

A unified multi-restaurant cart and checkout could encourage customers to add items from different restaurants in a single purchase.

Potential benefits:
- Reduced checkout friction
- Higher customer basket value
- Improved convenience for group and family orders

However, coordinating multiple restaurant pickups could increase fulfillment costs.

**Core question:** Would additional spending generate enough contribution to cover the incremental cost of multi-restaurant delivery?

### 2. Hypothetical Assumptions

| Variable | Assumption |
|---|---:|
| Monthly eligible customers | 10,000 |
| Feature adoption rate | 10% |
| Adopting customers | 1,000 |
| Multiorder transactions per adopter | 1/month |
| Incremental spending per adopted transaction | ₹100 |
| Contribution rate on incremental spending | 15% |
| Additional fulfillment cost per transaction | ₹20 |

These numbers are chosen to demonstrate a calculation method. They are not validated estimates.

### 3. Illustrative Calculations

**Adopting customers**

10,000 × 10% = 1,000

**Incremental GMV**

1,000 × ₹100 = ₹1,00,000/month

**Contribution from incremental spending**

₹1,00,000 × 15% = ₹15,000/month

**Additional fulfillment cost**

1,000 × ₹20 = ₹20,000/month

**Net incremental contribution**

₹15,000 − ₹20,000 = **−₹5,000/month**

### 4. Break-Even Analysis

Break-even incremental spend per adopted transaction:

₹20 / 15% = **₹133.33**

Under these assumptions, incremental customer spending must exceed approximately ₹133.33 per transaction to generate positive incremental contribution.

### 5. Product Trade-Offs

**Growth vs. profitability:** Higher basket value does not guarantee positive contribution.

**Convenience vs. delivery complexity:** Combining restaurant orders could improve checkout convenience while increasing delivery coordination costs.

**Adoption vs. customer value:** A higher adoption rate alone does not guarantee improved ordering frequency or profitability.

### 6. Proposed Measurement Strategy

**North Star Metric:** Orders per Eligible User, as defined in the existing project plan.

**Supporting metrics:**
- Multiorder adoption rate
- Checkout completion rate
- Average basket value
- Incremental contribution per adopted transaction
- Delivery delays and cancellation rates

A unified checkout may consolidate purchases previously recorded as separate orders. Therefore, order count must be interpreted alongside customer spending and contribution.

### 7. Product Recommendation

Retain the phased MVP approach:

1. P0 — Multi-Restaurant Cart
2. P1 — Single Checkout
3. P2 — Coordinated Delivery

Before scaling coordinated delivery, evaluate whether incremental contribution and operational reliability justify the additional complexity.

### 8. Limitations & Next Steps

This analysis has not been validated with real users or transaction data.

Future validation would require actual adoption, spending, order-frequency, incremental delivery-cost and cancellation data.

**Conclusion:** The hypothetical scenario illustrates why multiorder success should be evaluated through customer value, operational performance, and profitability — not adoption alone.
