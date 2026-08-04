## 2026-03-15 to 2026-03-31 - Archival UX, Keyboard Landmarks & Accesskeys
**Learning:** High-density, sensitive digital archives require resilient, standard-compliant HTML elements to guarantee perfect accessibility. Consolidating nested inline tag styles, using standalone HTML scroll anchors outside level-2 headings, and providing interactive `tel:` and `sms:` URI schemas reduces cognitive friction. Enclosing quick-navigation elements within semantic `<nav>` structures combined with underlined shortcut keys, platform-agnostic ARIA labels, and standard hover `title` tooltips bridges visual pointer interfaces with direct keyboard-first accessibility.
**Action:** Restructure markdown headers with clean headings, standalone scroll anchors, and enrich navigation bars with comprehensive, underlined browser accesskeys.

## 2026-04-01 - Safe External Escapes & Standardized Support Navigation
**Learning:** For highly sensitive digital archives, external helpline references must be rendered as semantic HTML anchors with `target="_blank"`, `rel="noopener"`, and visual indicators (`↗️`) so users do not lose their place. `aria-label` tags and `title` tooltips prevent screen-reader disorientation.
**Action:** Convert external support links to semantic HTML anchors featuring safe new-tab targets.

## 2026-04-02 - Inclusive Academic Citations for Multidisciplinary Research
**Learning:** In digital archives holding oral histories or sensitive primary source materials, academic users often span history, humanities, and social sciences. Providing the Chicago Manual of Style citation format alongside APA, MLA, and BibTeX inside pre-formatted code blocks allows academic researchers to copy references seamlessly.
**Action:** Always provide APA, MLA, Chicago, and BibTeX citation presets inside native codeblocks within collapsible citation sections.

## 2026-04-03 - Harvard Citation Style & Tab Security Hygiene
**Learning:** Adding Harvard citations supports multidisciplinary researchers (especially in biology, geology, and sociology), while applying `rel="noopener"` to online previews prevents security/performance hijacking issues (`tabnabbing`) to safeguard the user's browser session.
**Action:** Include Harvard reference models inside collapsible citations, and enforce `rel="noopener"` across all new tab external previews.
