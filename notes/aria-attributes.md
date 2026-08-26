# ARIA quick notes

Use native HTML first. ARIA only when needed.

## Common attributes

- `role` – changes semantics, avoid if a native element works
- `aria-label` – accessible name when there is no visible text
- `aria-labelledby` – references visible text as the accessible name
- `aria-describedby` – adds extra description or help text
- `aria-hidden="true"` – hides decorative content from assistive tech
- `aria-expanded` – state for disclosures and accordions
- `aria-current` – indicates the current item in a set
- `aria-live` – announces dynamic updates (`polite` or `assertive`)

## Notes

- Prefer native semantics over ARIA roles.
- Use `aria-labelledby` when a visible label already exists.
- Don’t rely on validators alone; test with a screen reader.
- Keep `tabindex` at `0` or `-1`; avoid positive values.