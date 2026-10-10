# PRD & Prototype Sprint (Module 4)

## Pick & scope with MoSCoW
- **The “Now” feature I’m scoping (name + one-line core description):** Fast Lane (Quick Relief Options):
A two-tap path for time-pressed, willing-to-pay consumers like Mara: they either buy a one-week grace period or set up a small instalment plan without income documents, so they can act now instead of abandoning the portal or calling an agent.
- **My finalized Must-Haves (after overriding the AI):** 1. Two-option entry screen
   "More time" / "Small instalments", with an upfront line: "No documents needed today."
   Moment of misery: removes the income/document trigger before it appears.

2. Plain-language "why we ask / when documents are needed"
   Shown on each option. Documents are only needed later for a longer deferral or a rate under €10. States what the contact data is used for (reminders only).

3. Grace extension,  covering both claims
   Date picker (max 7 days). The confirmation states the exact "log in by <date>" and what happens if she doesn't.

4. Minimum-rate plan, choosing one or  both claims  which are displayed by case number, amount, creditor
   €10 floor with an explanatory message if she enters less. First-payment date within 1 month.

5. Live consequence display
   End date, total interest and total payable, recalculated on every amount change.

6. "If you miss a payment" disclosure
   Plain language, shown before confirmation. 

7. Confirmation summary and reminder opt-in
   Summary of amounts, dates and claims agreed. Reminder opt-in with channel choice (email or SMS). For the extension this is mandatory, because the return date is the mechanism.

8. Visible "Need help?" path
   Static link/contact as the minimum support route for vulnerable consumers.
   Moment of misery: an escape that isn't a dead end (guardrail floor).

ENABLER (parallel, non-negotiable): event tracking for funnel, agreement, 7-day agent contact and 60-day missed payment. Required for the month-3 go/no-go.
- **What I demoted from Must → Should/Won’t, and why:** Eligibility check before Fast Lane access (rule-based, no model):   Has the extension or a Fast Lane plan already been used? Is there a broken agreement?

-> moved from must to should, because of the backend dependency, it can be delivered later, supported by first experiences and data.

## Generate your Simplified PRD
- **One thing my PRD makes explicit that a vague brief would have missed:** The PRD sets the success condition upfront: a gain in the headline metric (the SSR) only counts if the quality of the outcome holds (60-day miss rate is kept)

## Prompt-to-prototype sprint
- **Where did the prototype reveal a gap in my PRD logic? (what I had to update):** the actual new feature was already the first screen, there was an entry screen missing, explicitly offering that feature. Plus several details that needed correction.
- **My prototype, as a link or a screenshot (publish or share from your tool; in Lovable that is Share → Share Preview, in Bolt Publish → Web. No share URL? Screenshot the working flow):** Fast Lane_ Quick Relief Options.html
