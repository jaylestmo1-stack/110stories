## 2026-05-19 - Keyboard Scrollability and Focusability for Code Elements
**Learning:** Preformatted code elements (`<pre>`) inside collapsible details containers require explicit `tabindex="0"` and descriptive `aria-label` attributes to ensure keyboard-only and screen-reader users can focus and scroll horizontally through longer code blocks.
**Action:** Always add `tabindex="0"` and descriptive `aria-label` attributes to preformatted citation code blocks.

## 2026-05-19 - Standardized Multi-Line BibTeX Formatting
**Learning:** Single-line BibTeX blocks inside collapsible academic citation sections cause friction when imported into citation managers (e.g., Zotero, Mendeley, BibDesk). Standard multi-line indentation inside `<pre><code>` structures ensures frictionless copying and parsing while remaining fully compatible with Markdown sanitizers.
**Action:** Format BibTeX citations using standard multi-line indented key-value attributes inside preformatted code elements.
