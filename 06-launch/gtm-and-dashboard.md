# GTM Launch Plan, Riverty business-unit case

| Field | Value |
|---|---|
| Feature | Fast Lane (Quick Relief Options) |
| Goal | Conversion |
| Launch tier | S, Minimal |

## Goal & Audience
- **Goal:** Conversion, We chose conversion (sustained self-service resolution) because awareness is already covered by existing outreach, and engagement is the wrong target in the debt collection context.
- **Target audience:** Willing-to-pay consumers at the income/document step; Mara as design reference.
Secondary: Collection agents, who inherit incomplete cases from the portal.

## Launch Tier
- **S, Minimal**, S, because comms could steer consumers toward Fast Lane who don’t need it, raising default and portfolio risk. Entry through the income step filters for real intent. Plus: The new feature is discovered in-journey, outreach would contaminate the A/B test.

## Channels
1. **Owned: Portal, income/document step: Primary. The Fast Lane option appears here, with short copy explaining the option and what happens if a payment is missed.**
2. **Owned: Agent channel (phone): The current workaround. Agents know what Fast Lane is and can see who got it, so a consumer who calls isn’t treated like a blank slate.**
3. **Owned: transactional confirmation (screen plus email/SMS)**

## Enablement & Assets
agent one-pager and FAQ; agent view of Fast Lane status; instrumentation for the guardrails.

## Ownership, Budget & Timeline
- **Ownership & budget:** PM owns the plan, experiment, brief of agents and post-launch metrics. Design owns the in-step copy and layout. Eng owns the feature flag, eligibility rule, and rollback. Data owns SSR measurement and guardrails. Compliance/Legal sign off before launch. No marketing or paid budget needed.
- **Timeline:** Beta: readiness and sign-offs. Launch: controlled 50/50 pilot, no external outreach. Post-launch: 90-day maturation, then a pre-agreed ship, iterate or stop decision.

## Success Metrics
- **Metrics:** SSR is the primary conversion metric. The 60-day missed-payment rate and 90-day payments per consumer are guardrails, so a rise in SSR can’t come from plans that fail or recover less.
- **Bad signal to watch for:** rises while 90-day payments per consumer fall, or missed payment agreements rise.
- **Likely post-launch decision:** Most likely: iterate. SSR should rise, but the missed-payment guardrail may be underpowered at pilot volume, so we extend enrolment or split the document skip from the plan cap before expanding.
