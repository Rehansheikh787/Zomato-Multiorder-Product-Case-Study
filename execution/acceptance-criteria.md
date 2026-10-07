# Acceptance Criteria

The working framework uses **P/Q/R/S/T/U**: Performance, Quality, Reliability, Security, Transparency and Usability.

Only criteria finalized in the working session are documented as approved. Criteria for the remaining stories stay open rather than being inferred.

## US1 — Add Items from Another Restaurant

| Dimension | Approved acceptance criterion |
|---|---|
| Performance | Cart should update within the defined response-time target. |
| Quality | The item should be added correctly without altering existing cart items. |
| Reliability | If adding the item fails, existing cart items should remain intact and the user should receive a clear error message. |
| Security | The item should be added only to the signed-in user's cart. |
| Transparency | Price and availability should be clearly displayed. |
| Usability | The user should have a clear add action and receive confirmation. |

## US5 — Review Multi-Restaurant Order

| Dimension | Approved acceptance criterion |
|---|---|
| Performance | The complete order summary should load within the defined response-time target. |
| Quality | All selected items should be displayed correctly under their respective restaurants. |
| Reliability | If an item becomes unavailable before payment, it should be clearly identified and unaffected selections should be retained. |
| Security | Payment initiation should use the existing secure payment infrastructure. |
| Transparency | Item prices, applicable fees, discounts and final payable amount should be clearly displayed. |
| Usability | The next step toward payment should be clear and require minimal unnecessary actions. |

## Open acceptance criteria

The P/Q/R/S/T/U criteria for **US2, US3, US4, US6, US7 and US8** were not finalized in the source working session. They remain intentionally open.

The numeric response-time target is also not defined yet; no number is assumed here.
