# Manual Review Cases — Complex Retention Decisions

This document details **10 specific customer cases** from our database where retention decisions are not straightforward. We analyze their behaviors, support history, and digital footprints to recommend customized, high-ROI actions.

---

### Case 1: CUST00332 — High-Spend, Frustrated, and Digitally Silent
*   **Segment:** High-Value Unhappy (Retained in target window: Yes/0)
*   **Key Metrics:** Recency: 24 days, Frequency (180d): 2, Monetary (180d): ₹2,059.80, Return Rate (180d): 50%, Average Rating (180d): 1.5, Ticket Count (90d): 2, Negative Ticket Rate: 100%, Web Sessions (30d): 0.
*   **The Problem:** This is a high-spending customer who placed two orders, returned half of their items, and gave an extremely low rating of 1.5. They contacted support twice (both times negatively resolved), and have since completely stopped visiting our site/app (`sessions_30d == 0`), indicating they are actively boycotting our brand.
*   **Recommended Action:** **VIP Outreach.** Do NOT send a standard email discount (which would insult them). Have a senior customer support agent call or send a personal email apologising for their support experience, confirming their refund is processed, and providing a ₹500 store credit voucher to show goodwill.

### Case 2: CUST00713 — Active VIP Spender with Low Satisfaction
*   **Segment:** High-Value Unhappy (Retained in target window: Yes/0)
*   **Key Metrics:** Recency: 3 days, Frequency (180d): 4, Monetary (180d): ₹3,625.93, Return Rate: 25%, Avg Rating: 2.25, Ticket Count: 2, Negative Ticket Rate: 50%, Sessions (30d): 10.
*   **The Problem:** An extremely active VIP buyer who placed an order 3 days ago, but has a low average rating (2.25) and raised support issues. Unlike `CUST00332`, they are still digitally active (10 sessions).
*   **Recommended Action:** Proactive support callback. A support agent should contact them immediately to resolve the open issue from their recent purchase before it leads to disengagement. Offer a VIP membership upgrade.

### Case 3: CUST00438 — Premium Loyalty Churner with 100% Returns
*   **Segment:** At-Risk (Retained in target window: No/1 - Churned)
*   **Key Metrics:** Recency: 64 days, Frequency: 3, Monetary: ₹2,466.39, Return Rate: 1.0 (Returned all items), Loyalty Tier: Platinum, Ticket Count: 2, Negative Tickets: 100%, Support Resolution Time: 36.05 hours (Very high).
*   **The Problem:** Despite being a Platinum loyalty tier customer who spent ₹2,466.39, they returned *every single purchase* in the last 180 days. They also had support complaints that took a massive 36 hours to resolve. They subsequently churned.
*   **Recommended Action:** **Product & Operations Audit.** This customer highlights a systemic risk: high-value customers returning everything due to poor quality or fit, exacerbated by slow customer support. No promotion will win them back; we must audit the Baby Care product line (their preferred category) and support response SLAs.

### Case 4: CUST00084 — Dormant Order Book but Active Window Shopper
*   **Segment:** Dormant (Retained in target window: No/1 - Churned)
*   **Key Metrics:** Recency: 167 days, Frequency: 1, Monetary: ₹1,273.18, Loyalty Tier: Silver, Sessions (30d): 11, Product Views: 60, Cart Adds: 5, Abandoned Carts: 2.
*   **The Problem:** This customer has not purchased an item in 167 days, placing them in the "Dormant" category. However, they are highly active on our website (11 sessions, 60 product views, and 5 cart additions in the last 30 days). They are displaying extreme purchase intent but are hesitant to complete checkout.
*   **Recommended Action:** **Cart Abandonment Trigger.** Send a high-incentive, personalized email offering a 20% discount or a free sample product with purchase specifically for the items left in their cart, reminding them of their Silver loyalty perks.

### Case 5: CUST00189 — Dormant Shopper who Eventually Converted
*   **Segment:** Dormant (Retained in target window: Yes/0)
*   **Key Metrics:** Recency: 140 days, Frequency: 1, Monetary: ₹574.39, Sessions (30d): 10, Product Views: 52, Cart Adds: 4, Abandoned Carts: 1, Churn: 0.
*   **The Problem:** Similar to `CUST00084`, this customer was dormant by transaction date but highly active digitally. They did not churn (they placed a transaction inside the target window).
*   **Recommended Action:** This confirms that high digital activity among dormant buyers is a critical conversion signal. We should automate "We noticed you looking" push notifications to accelerate checkout.

### Case 6: CUST00263 — Platinum Spender with High Return Rate
*   **Segment:** Loyal Customers (Retained: Yes/0)
*   **Key Metrics:** Recency: 25 days, Frequency: 3, Monetary: ₹1,618.39, Return Rate: 66.7%, Loyalty Tier: Platinum, Ticket Count: 2, Negative Tickets: 0.0, Sessions (30d): 15.
*   **The Problem:** A frequent and highly active buyer (15 sessions) in the Platinum tier. However, they return 2/3 of their purchases. This erodes their net value.
*   **Recommended Action:** **Fit/Routine Consultation.** Offer a free, online 1-on-1 skin/hair consultation (their preferred category is Wellness) to help them select products that fit their skin type directly, reducing return shipping overhead and building loyalty.

### Case 7: CUST00097 — Digitally Silent Offline Buyer
*   **Segment:** Champions (Retained: Yes/0)
*   **Key Metrics:** Recency: 1 day, Frequency: 3, Monetary: ₹2,946.09, Rating: 2.33, Sessions (30d): 0, Email Opens: 0, Campaign Clicks: 0.
*   **The Problem:** This customer ordered yesterday and has high spend, but has 0 app sessions and 0 email opens in the last 30 days. They also gave a low average satisfaction rating (2.33). How do they buy without web activity? They might purchase through third-party marketplaces or via telephone orders.
*   **Recommended Action:** Reach out via SMS or delivery package inserts. Ask for feedback on their delivery experience since they do not open marketing emails, and offer a simple feedback channel.

### Case 8: CUST00010 — Highly Active, Newly Acquired Discount Hunter
*   **Segment:** Discount-Sensitive (Retained: Yes/0)
*   **Key Metrics:** Days since signup: 28, Recency: 9 days, Frequency: 1, Monetary: ₹636.80, Average Discount: 45%, Sessions (30d): 13, Product Views: 71, Cart Adds: 3, Abandoned Carts: 2.
*   **The Problem:** This customer signed up 28 days ago, browsed extensively (13 sessions, 71 views), but only placed a single order using a deep 45% discount. They are highly active but margin-dilutive.
*   **Recommended Action:** Transition them using bundle discounts. Instead of blanket percentage off, offer a "buy 2 get 1 free" package or threshold discount (e.g. ₹200 off on ₹1,200 spend) to increase their average order value.

### Case 9: CUST00049 — Newly Acquired Marketplace Deal Seeker
*   **Segment:** Discount-Sensitive (Retained: Yes/0)
*   **Key Metrics:** Days since signup: 32, Recency: 8 days, Frequency: 1, Monetary: ₹380.83, Average Discount: 47%, Acquisition Channel: Marketplace.
*   **The Problem:** Acquired via an external marketplace channel. They placed a low-value order with a 47% discount.
*   **Recommended Action:** Onboard them to the brand's own app/website. Send a first-purchase app discount offer to shift them away from third-party marketplace commissions.

### Case 10: CUST00550 — Low-Engagement Casual Buyer
*   **Segment:** New Customers (Retained: Yes/0)
*   **Key Metrics:** Days since signup: 66, Recency: 11 days, Frequency: 1, Monetary: ₹525.80, Average Discount: 42%, Sessions (30d): 0, Email Opens: 0.
*   **The Problem:** Ordered 11 days ago with a high discount, but has zero digital activity.
*   **Recommended Action:** Focus on post-purchase customer satisfaction emails or SMS. Keep them informed about product usage instructions to encourage repeat orders without discounting.
