# A/B Experiment Brief, Riverty business-unit case

## Parameters
| Parameter | Decision |
|---|---|
| Feature under test | Fast Lane (Quick Relief Options) |
| Persona | Willing-to-pay consumerswith limited time and a liquidity constraint |
| Expected outcome | a raise of Self-Service rate (cases that are resolved (the consumer paid, or successfully set up an instalment plan) with no inbound contact in the 30 days before or after resolution) |
| Primary success metric | Self-Service Rate (SSR) |
| Baseline rate | 30% |
| Guardrail metric | New agreements missing a payment within 60 days |
| Guardrail boundary | -3% |
| Second guardrail | Day-90 payments collected per journey starters |
| Minimum Detectable Effect | +3% |
| Sample size per arm | 4000 |
| Traffic split | 50/50 |
| Test duration | 4 months |
| Significance threshold | 95% |

## Control vs. Variant
- **Control (A):** The moment the journey asks for her income or documents. She doesn't know why it's asking, whether the plan will be affordable, what happens if she misses a payment, whether both claims can be handled together, or whether accepting could make things worse. 

Current workaround: Phone call to an agent
- **Variant (B):** For willing-to-pay yet  time- constrained consumers who reach the income/document step, we believe offering a Fast Lane option, offering document-free small plan under certain approved preconditions) will increase Sustained SSR by ≥3pp absolute (baseline 30%) within a 4-month enrollment window plus 60-day maturation, while the 60-day missed-payment rate does not rise by more than 3pp.
- **Held constant (isolation check):** the payment journey itself with its payment options and background processes

## Hypothesis
> I believe that Fast Lane (Quick Relief Options) for Willing-to-pay consumerswith limited time and a liquidity constraint will result in a raise of Self-Service rate (cases that are resolved (the consumer paid, or successfully set up an instalment plan) with no inbound contact in the 30 days before or after resolution), as measured by a +3% change in Self-Service Rate (SSR) within 4 months. We will protect New agreements missing a payment within 60 days throughout the test.

## Shipping criteria
> We will **ship** if Self-Service Rate (SSR) improves by ≥ +3% at 95% and New agreements missing a payment within 60 days does not reach -3% after 4 months.
> We will **iterate** if direction is positive but lift is below the MDE.
> We will **kill** if the primary metric shows no improvement or moves negatively.
> The read date is fixed at the end of 4 months, no results reviewed before this date.
