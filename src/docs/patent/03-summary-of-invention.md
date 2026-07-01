# Summary of the Invention

**Version:** 0.1

---

# Overview

The present invention provides an automated insurance system and method for determining insurance premiums and claim payments for property whose market value may change during the policy term.

Unlike traditional insurance products that rely upon a Scheduled Value established at policy inception for premium determination and, in many cases, claim settlement, the present invention dynamically determines Market Value throughout the policy period using one or more insurer-approved valuation methodologies.

The invention separates the functions of establishing an initial Deposit Premium, determining the Final Earned Premium, and settling claims, allowing each function to utilize valuation information appropriate to its purpose.

The disclosed system is intended to provide a more accurate alignment between insurance premiums and the insurer's actual exposure throughout the policy period while simultaneously ensuring that claim payments reflect current market conditions at the time of loss. By automating the determination of market values during the policy term, the system benefits both insurers and insureds through more accurate pricing, reduced administrative effort, improved transparency, and greater consistency in policy administration.

---

# Deposit Premium

At policy inception, the insured schedules one or more items of property and declares a Scheduled Value for each item.

The Scheduled Value serves as the basis for calculating the Deposit Premium due at policy inception.

The Scheduled Value is not intended to represent the final basis for determining the earned premium or the amount payable upon a covered loss.

---

# Market Value Determination

Throughout the policy period, the insurer periodically determines the Market Value of each insured item using one or more approved valuation methodologies.

The valuation methodology may utilize any combination of internal valuation models, third-party valuation services, publicly available market information, proprietary algorithms, manual review, or other valuation techniques selected by the insurer.

The invention is independent of any particular valuation methodology and is intended to accommodate existing and future valuation technologies.

---

# Final Earned Premium

At the conclusion of the policy period, the insurer determines the Time-Weighted Average Market Value for each insured item based upon the Market Values determined during the policy period.

The Final Earned Premium is calculated by applying the applicable premium rate to the Time-Weighted Average Market Value.

The Deposit Premium previously paid by the insured is credited against the Final Earned Premium.

If the Final Earned Premium exceeds the Deposit Premium, the insured is responsible for the additional premium.

If the Deposit Premium exceeds the Final Earned Premium, the insurer refunds the excess premium to the insured.

Because Market Values are determined periodically throughout the policy period, the Final Earned Premium reflects the insurer's actual exposure over time rather than a single Scheduled Value established at policy inception. This approach provides a more equitable allocation of premium between the insurer and the insured while substantially reducing the need for routine policy endorsements solely to maintain current insured values.

---

# Claim Settlement

If a covered loss occurs during the policy period, the insurer determines the amount payable using the Market Value applicable immediately preceding the Date of Loss, subject to all other policy provisions.

Accordingly, claim settlement reflects the current Market Value at the time of loss rather than the Scheduled Value established at policy inception.

---

# Transparency

The invention further provides transparency by allowing the insured to review the valuation history, valuation methodology, and supporting information used in determining both premium and claim payments.

This transparency promotes consistency, reduces valuation disputes, and improves confidence in the claim settlement process.

---

# Flexibility

The invention is intended to support insurer-specific business rules, valuation methodologies, premium calculation methods, underwriting guidelines, and claim handling procedures without departing from the underlying principles of the invention.

Accordingly, the invention is not limited to any particular insurance product, valuation source, computer architecture, algorithm, or class of insured property.

The disclosed system enables insurers to administer policies whose premiums and claim settlements remain aligned with changing market conditions throughout the policy period with substantially reduced reliance upon manual policy modifications, while preserving the insurer's ability to perform underwriting, claims handling, and valuation review whenever appropriate.

---

## Revision History

### Version 0.1

- Initial draft.