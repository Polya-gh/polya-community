# Templates

Official templates for writing Polya problem sheets.

Alternatively, submit problems via the form at [polya.live/contribute](https://polya.live/contribute), no git knowledge required.

---

## Files

| File | Format |
|---|---|
| `problem.tex` | LaTeX |
| `problem.typ` | Typst |

---

## Custom Templates

Coming soon.

---

## Required Variables

Every problem must define these. The script will reject the file if any required field is missing or uses an invalid value.

| Variable | Required | Valid Values |
|---|---|---|
| `title` | ✓ | Any string |
| `subject` | ✓ | `mathematics`, `physics` |
| `topic` | ✓ | e.g. `calculus`, `mechanics` |
| `subtopic` | ✓ | e.g. `calculus-1`, `linear-motion` |
| `difficulty` | ✓ | `easy`, `medium`, `hard`, `ipho` / `imo` |
| `points` | ✓ | `80`, `150`, `250`, `400` |
| `statement` | ✓ | Math markup string |
| `answer` | ✓ | Exact number or expression |
| `solution` | ✓ | Full worked out solution |
| `hint` | — | Optional statement |
| `source` | — | Competition or textbook citation |

---

## Difficulty Guide

| Level | Description | Points |
|---|---|---|
| `easy` | direct application | 80 |
| `medium` | Two or more concepts combined | 150 |
| `hard` | Non-obvious, competition-level | 250 |
| `ipho` / `imo` | IPhO / IMO difficulty | 400 |
