# Adaptation notes

The Codex reference is the dark Ayu family. The official Ayu palette project publishes native Light, Dark and Mirage variants; this package pairs Light and Dark and does not claim Ayu Light is a Codex-native preset or include Mirage.

## Sources

- palette and variants: https://github.com/ayu-theme/ayu-colors/tree/d461f02983546636bc6e1e0c48190fdb74036426
- package metadata: https://github.com/ayu-theme/ayu-colors/blob/d461f02983546636bc6e1e0c48190fdb74036426/package.json (ayu 9.1.0; author Konstantin Pschera; MIT)
- license: https://github.com/ayu-theme/ayu-colors/blob/d461f02983546636bc6e1e0c48190fdb74036426/license

## Mapping decisions

- Light background and text use official Ayu Light; dark background and text use Ayu Dark. Official values anchor the mapping; tiered Tine surfaces are semantic adaptations.
- Light secondary text, link and tag use deeper colors for contrast (#626A70, #24668D and #5C7418). Dark amber accent, blue link and green tag follow the Ayu Dark families.
- Selection, inline-code and mark roles adapt the palette to Tine's supported 21-color API. Fonts, task markers and arbitrary UI rules are outside this package.

## Local validation

See the [local check summary](local-check.md) for the exact tested combinations and current manifest digest. User screenshots and full Tine interaction acceptance are pending.

## Codex reference verification

- Ayu's official upstream palette includes Light, Dark and Mirage; this package pairs the native Light and Dark variants, matching the simple Ayu family, and does not merge Mirage into either mode.
- Light canvas and foreground follow Ayu Light (#FCFCFC and #5C6166); dark canvas and foreground follow Ayu Dark (#0F1419 and #BFBDB6). Tiered Tine surfaces are semantic adaptations.
- Light link is deepened from the bright source blue to #24668D and tag from #86B300 to #5C7418 for readable semantic text; light secondary text is #626A70. Dark orange accent, cyan-blue link and green tag use Ayu Dark families.
- Selection, inline code and amber marks are adapted to Tine's supported color roles. The 21-token API does not control fonts, task markers, arbitrary hover rules or every syntax color.
- The dark canvas #10141c matches the installed Codex Ayu reference; it differs slightly from upstream ayu-colors dark canvas #0f1419.


Release 0.1.1 retains the tested 0.1.0 color tokens and adds publication metadata and pinned screenshots.

See the [local check summary](local-check.md) for the exact tested combinations and manifest digest.
