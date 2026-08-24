## 2026-05-19 - Keyboard Scrollability and Focusability for Code Elements
**Learning:** Preformatted code elements (`<pre>`) inside collapsible details containers require explicit `tabindex="0"` and descriptive `aria-label` attributes to ensure keyboard-only and screen-reader users can focus and scroll horizontally through longer code blocks.
**Action:** Always add `tabindex="0"` and descriptive `aria-label` attributes to preformatted citation code blocks.
