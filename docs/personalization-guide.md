# Personalization guide

The framework is most useful when the adopter defines relevance and evidence policies deliberately. Work privately; the public examples are fictional teaching profiles and are not defaults or recommendations for any organization.

| Decision | Questions to answer | Where to apply |
|---|---|---|
| Scope | Which asset categories and dependencies matter? Which are out of scope? | Relevance profile and shared prompt |
| Relevance | Which findings require direct attention, coordination or awareness? | P1–P3; separate from severity |
| Sources | Which official advisory feeds, registries and research sources cover the scope? Are they accessible? | Source registry and approved sources |
| Alert criteria | Which material changes justify interrupting a person? What evidence is enough for a provisional alert? | Conditional alert prompt |
| Evidence | How should partial primary evidence, secondary evidence and early signals be handled? | Shared policy and verification model |
| Timing | What latency is tolerable? What polling, batching and scheduling delays exist? | Private schedules |
| Delivery | Who is authorized to receive which outputs? What language and detail are useful? | Delivery scope and output preferences |
| Coverage | What is a material source failure? When should it trigger a separate warning? | Coverage policy |

## Worked workflow

Start with the empty templates. Compare the fictional examples to understand the shape of each decision. Replace every example choice with an independently selected private value. Translate the resulting values into the parameterized prompts manually. Do not assume the assistant reads YAML automatically. Review the combined prompts for contradictory criteria, undefined placeholders and excess disclosure. Confirm the actual service supports the desired schedule and permissions.

## Evaluate and refine

Use synthetic test fixtures for duplicates, partial evidence, unavailable sources, untrusted instructions and material changes. Compare actual collection against a manually verified sample; record evidence quality, missed findings and latency privately. Change policy based on observed results, not isolated noise. Keep private inventory, routing, timings, source selections and populated prompts outside public repositories.
