# Accessibility Checklist

Quick reference for frontend work.

## Semantic HTML
- Use landmark elements (`header`, `nav`, `main`, `footer`).
- Use one `h1` per page, heading hierarchy.
- Use native buttons/links over divs.

## Keyboard
- All interactive elements focusable.
- Visible focus indicator.
- No keyboard traps.

## Forms
- Labels associated with inputs.
- Error messages linked via `aria-describedby`.
- Required fields indicated.

## Media
- Alt text for meaningful images.
- Captions/transcripts for video/audio.
- No autoplaying media.

## Color & Contrast
- Contrast ratio at least 4.5:1 text, 3:1 large text.
- Don't rely on color alone.

## ARIA
- Prefer native HTML over ARIA.
- Use `aria-expanded`, `aria-current` when needed.
- Test with screen readers.
