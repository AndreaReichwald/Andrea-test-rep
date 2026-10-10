# Roadmap, PRD & Prototype (Module 4)

## Your strategic anchors
- **Persona (M2), who are you solving for?:** Mara, 38, the consumer: A shift worker with two open claims and a stable but variable income, who can't pay the full amount at once.
- **Primary success metric (M3), your leading indicator:** payment agreements among journey starters, not contacting an agent within 7 days
- **Moment of misery (M2), the specific friction blocking the goal:** The moment the journey asks for her income or documents. She doesn't know why it's asking, whether the plan will be affordable, what happens if she misses a payment, whether both claims can be handled together, or whether accepting could make things worse. If she can't help herself, she gives up and calls an agent. This matches the research themes on affordability, "why this information" and fear of consequences.
- **Guardrail metric (M3), what must not drop or break:** 60-day plan-keep rate

## Scan the backlog & set a human baseline
- **My instinctive “quick wins” before touching the AI (2 to 3 feature IDs + why):** - Why-We-Ask Explainers for journey steps
- show multiple cases, even if overarching payment agreements are not supported in the backend
- offer fast-lane self service for willing-to-pay consumers

## Audit, override & decide
- **Where did you override the AI? (feature + old vs. new score + why):** Fast Lane: old score: V3 / E3. new score: V5/E2 because it's an easy-to-build feature that promises to raise trust and reduce churn and unnecessary contacts for consumers like Mara

Light Affordability Check: V5 / E3. - new: V3/E3 because AI assumed wrongly that an income range can replace income/documents in case they are needed for justification of a minor rate.
- **Did the AI over-value a Sales/Eng request your M2 interviews don’t support?:** not after some iterations/clarifications
- **Did it underweight something your M3 cohort/funnel data strongly supports?:** not after some iterations/clarifications

## Generate your interactive roadmap
- **My “Now” lane (this sprint), the 2 to 3 quick wins I’ll build first:** #1 Fast Lane (V5 · E2)
#2 “What Can I Afford?” Slider (V4 · E2)
#4 Why-We-Ask Explainers (V4 · E1)
- **What I cut, and the “no” I’m protecting the scope from:** Multiple case instalment agreements with backend integration
- **Prototype/roadmap screenshot link (paste into your deliverables):** a-fair-way-forward-roadmap.html
