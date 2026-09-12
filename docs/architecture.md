# Architecture Notes

## Pre-challenge default

```text
                         INPUT
                           │
                           ▼
                Deterministic normalizer
                           │
                           ▼
                      Agent core
                     bounded loop
                           │
              ┌────────────┼────────────┐
              ▼            ▼            ▼
           retrieval     Python      domain tool
              │            │            │
              └────────────┼────────────┘
                           ▼
                  Structured evidence
                           │
                           ▼
                  Deterministic policy
                           │
                           ▼
                    Schema validator
                           │
                           ▼
                       Safety gate
                           │
                           ▼
                         OUTPUT
```

This is a hypothesis. Replace or simplify it after the September problem is released.

## Design rules
- deterministic computation belongs in code;
- model behavior should be bounded and observable;
- evidence identifiers must be validated against source data;
- safety-critical consequences should not depend only on prompts;
- every major abstraction needs a measurable reason to exist.
