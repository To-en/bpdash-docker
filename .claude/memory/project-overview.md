---
name: project-context
description: {{Project name | one-line purpose and tech summary}}
metadata:
  type: project
---

Project is a **{{experiment / product / tool / service}}**: {{one sentence on what it does and why it exists}}.

**Why:** {{The motivation — learning goal, business need, personal curiosity.}}
**How to apply:** {{How this context should shape suggestions.}}

---

## Domain

**What**: {{What users do and what the app enables.}}

**Users**:
- **{{Role A}}** — {{what they do, any username/access pattern worth noting}}
- **{{Role B}}** — {{what they do}}

**Peak load**: {{User count. Traffic pattern — constant / spiked / bursty. Peak conditions.}}

**Core flow**:
1. {{Step 1}}
2. {{Step 2}}
3. {{Step 3}}

**{{Entity}} lifecycle**: `{{state A}} → {{state B}} → {{state C}}`

---

## Stack

{{Languages, frameworks, infra. Mark uncertain choices with "TBD".}}

---

## Data Model

**{{Entity A}}**:
```
{ {{fields}} }
```
{{Notable fields or constraints.}}

**{{Entity B}}**:
```
{ {{fields}} }
```
{{Notable fields or constraints.}}

---

## Services

**{{Service A}}** (`{{path/}}`, {{framework}}, port `{{port}}`):
{{Responsibility. What it owns. Who calls it.}}

**{{Service B}}** (port `{{port}}`):
{{Responsibility.}}

---

## Key Files

### {{Group A}}
| File | Role |
|---|---|
| `{{path}}` | {{what it does}} |

### {{Group B}}
| File | Role |
|---|---|
| `{{path}}` | {{what it does}} |

---

## API Endpoints

### {{Resource A}}
| Method | Path | Access | Purpose |
|---|---|---|---|
| {{METHOD}} | `{{/path}}` | {{who}} | {{what}} |

---

## Infrastructure

**Local dev**:
```
{{commands to run locally}}
```

**Target**: {{Desired infra — Docker Compose, cloud, etc.}}

**Seed**: {{What sample data exists, where it lives, format.}}