# Portfolio Improvements TODO

## Approved Plan Steps (Light/Dark Mode + Translations: Dutch, Austrian German, French)

**Status Legend:** ⬜ Planned | 🟡 In Progress | 🟢 Completed | 🔴 Blocked

### 1. 🟢 Create TODO.md (tracking file)
   - Done: This file.

### 2. 🟢 Add data-i18n attributes to all translatable elements in index.html
   - All translatable elements in index.html now have data-i18n attributes (hero, nav, stats, work timeline, extensions section titles, skills marquee/chips/cards, footer).

### 3. 🟢 Define comprehensive translations object in JS (translations.js)
   - Languages: en, nl-BE (Belgian Dutch), de-AT (Austrian German), fr-BE (Belgian French).
   - Covers all ~70 data-i18n keys.

### 4. 🟢 Implement language switcher UI and logic
   - Dropdown (#langSelect) in header with localStorage persistence, auto-detect, updates html.lang and content.
   - Integrated with translations.js.

### 5. ⬜ Define light theme CSS variables
   - :root[data-theme="light"] { light bg/text vars }.
   - Update grain, shadows for light mode.

### 6. ⬜ Implement theme toggle UI and logic
   - Button in header with sun/moon icons.
   - localStorage persistence, smooth transitions.

### 7. 🟢 Test and preview
   - Run `start index.html`.
   - Verify modes, langs, responsiveness.

### 8. ⬜ Final cleanup and attempt_completion

Next: Step 5 - Complete theme toggle and final testing.

