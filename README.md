# Professor Philippa Hastings — UKRI-BBSRC Specialist

Version 1.0.0

A reusable persona-led skill for rigorous, constructive assessment of UK bioscience doctoral and early-career fellowship applications. Based on the user's supplied Professor Philippa Hastings profile, with modular references and practical review templates.

## Use

Load the skill with your runtime's supported skill mechanism, then provide the application material and scheme details. Example prompts:

- “Professor Philippa Hastings, assess this personal statement for MIBTP using the attached selection criteria.”
- “Phillipa Hastings, review my CV for this BBSRC DTP and explain the three most important improvements.”
- “Assess this FLF proposal for independence, feasibility and host fit.”
- “Run a mock iCASE interview. Ask one question at a time.”
- “Improve this passage while preserving my own wording.”

Provide the advert, published rubric, word limit and stage if available. The skill can offer provisional analysis when details are incomplete.

## Contents

- [Core skill](SKILL.md): activation and assessment workflow.
- [Persona](references/persona-and-boundaries.md): voice and character background.
- [Doctoral rubric](references/doctoral-assessment.md): default 30/25/20/15/10 weights, PIER and rapid scan.
- [Fellowship rubric](references/fellowship-assessment.md): default 40/30/15/10/5 weights and shortlist dashboard.
- [Funding verification](references/funding-verification.md): checking current rules when relevant.
- [Worked examples](references/worked-examples.md): doctoral statement, fellowship proposal and iCASE interview.
- [Review template](templates/application-review.md): six-part assessment.
- [Interview template](templates/interview-preparation.md): preparation and interactive practice.
- [Evaluation scenarios](evaluations/test-cases.md): 14 behavioural tests for future runtime evaluation.

## Accuracy note

Professor Hastings and Russell Square University are fictional. Scores are illustrative; current funding rules require verification. The skill does not claim actual panel credentials or privileged admissions access. It does not include the standalone safeguards section removed at the user's request.

## Installation and compatibility

The ZIP contains one top-level `philippa-hastings` directory. Import that folder/ZIP using your host's supported skill interface. Hosts that support Markdown Agent Skills can use SKILL.md and its relative references; automatic discovery and slash-command syntax vary. No scripts, credentials, external packages or MCP services are required for basic review. Current-rule verification requires browsing or supplied official sources. No active installation was performed during creation.

The skill overlaps with a general UKRI assessor; explicitly invoke Professor Hastings when this persona is preferred. No dependency on that other skill is required.

## Validation

See VALIDATION.md for the checks actually performed and limitations. Behavioural test cases are provided, not claimed as passed. No licence grant beyond the user's underlying rights is inferred by this package.
