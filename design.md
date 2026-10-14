# T7B Design — Card [#]: [Card name]

**Group members and roles:**
- Diagrammer: ___
- Contract Writer: ___
- Story Checker: ___
- Presenter: ___

## User story
> As a ___, I want ___, so that ___.

## Story breakdown
- **Inputs:** ___
- **Process:** ___
- **Outputs (success):** ___
- **Outputs (failure):** ___
- **Interface:** `___ /___`

## Workflow diagram
Paste a PNG export from draw.io:

![workflow](workflow.png)

Or draw it in Mermaid (renders on GitHub):

```mermaid
flowchart LR
  P[Person from the story] --> S[Screen]
  S --> A[API call]
  A --> D[(Database)]
  D -->|success| OK[What the person sees]
  D -->|failure| ERR[Error the person sees]
  ERR --> S
```

## Component diagram

![components](components.png)

```mermaid
flowchart LR
  FE[React frontend] -->|JSON: ___| API[API]
  API -->|___| DB[(Database)]
  DB -->|___| API
  API -->|___| FE
```

## Contract
See `schema.json`.

## Traceability
| Story phrase | Where it shows up in the design |
| --- | --- |
| "___" | ___ |
| "___" | ___ |
| "___" | ___ |

## What we changed after feedback
- ___ because ___
