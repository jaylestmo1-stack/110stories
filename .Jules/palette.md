## 2026-05-19 - Avoiding Accesskey Conflicts in Screen Reader Navigation
**Learning:** HTML `accesskey` attributes can override and conflict with screen reader keybindings (JAWS, NVDA, VoiceOver) and standard browser navigation shortcuts. Avoiding `accesskey` tags ensures assistive technology users maintain predictable, unhindered keyboard navigation.
**Action:** Prefer standard HTML semantic landmarks (`<nav>`, `<main>`, `<header>`) and skip links over `accesskey` attributes for keyboard navigation.
