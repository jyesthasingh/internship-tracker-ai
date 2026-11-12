# AI feature eval: resume-version suggestion

**What "good" means:** picks the version that best matches the JD, gives reasons grounded in the JD text, never invents experience.

## Test cases (write 20-30; mix types)
| # | Type | Input (JD summary + versions) | Expected | Actual | Pass? | Notes |
|---|---|---|---|---|---|---|
| 1 | Clear match | [ ] | [ ] | | | |
| 2 | Two close matches | [ ] | [ ] | | | |
| 3 | JD missing details | [ ] | Says it is unsure | | | |
| 4 | Trap: asks for skill I lack | [ ] | Does not claim it | | | |

## Results
- Pass rate round 1: [ ]/[ ]
- Failure patterns: [ ]
- What I changed: [prompt / rules]
- Pass rate round 2: [ ]/[ ]
