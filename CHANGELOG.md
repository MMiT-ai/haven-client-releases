# Changelog

Only changes included in public GitHub releases are listed here. Local test builds and work in progress are intentionally excluded.

## Version 0.1.7 - July 18, 2026

- Added Dream Bot with serpentine Dream Catcher harvesting, obstacle-aware routing, multiple ordered storage containers, automatic full-container fallback, persistent per-character container selections, and live container highlighting.
- Added Tree Harvest Bot with searchable species filters, selective seed, fruit and bough gathering, optional tree chopping and stump removal, and rectangular-area deforesting.
- Added Plow Bot for selecting and plowing rectangular fields with automatic plow selection, efficient lane ordering, path visualization, and safe movement handling.
- Added inventory content sidebars and sorting controls to server inventories and containers, including quality grouping and normal item interaction shortcuts.
- Added temporary shared object pings and expanded minimap icon controls with category filtering, bulk visibility controls, and additional vehicle icons.
- Improved automation routing around object collision shapes and dense object layouts while keeping claim, water, and wildlife safety behavior.

## Version 0.1.6 - July 15, 2026

- Added the Discovery Bot for finding and gathering unique products from trees, bushes, surface boulders, and forageables, with per-character discovery tracking, optional auto-drop and bough filtering, live progress, and frontier exploration.
- Improved shared bot pathfinding with personal and village claim avoidance, object collision routing, deep-water safety, controlled shallow-water crossings, aggressive-animal escape behavior, and recovery from failed cliff crossings.
- Added configurable aggressive-animal highlighting and automatic escape behavior for automation bots.
- Added planned bot-path visualization with individual bot toggles, a global setting, and a configurable keybinding.
- Added English help and usage instructions to every bot window, and improved bot responsiveness around empty or already completed natural resources.

## Version 0.1.5 - July 15, 2026

- Added configurable Auto Pick Critters automation with multi-select filters, an adjustable pickup radius, target highlighting, and an Alt+Q quick action for collecting all nearby critters.
- Redesigned the custom options pages with a clearer two-column layout, reorganized color settings, improved tooltips, and live overlay color updates.
- Added configurable camera movement smoothing for reduced visual jitter.
- Added optional remaining-time displays for curiosities and an option to require Shift before opening stack hover inventories.

## Version 0.1.4 - July 14, 2026

- Fixed the client incorrectly reporting that it was outdated after a successful update. Release builds now always use fresh version information.

## Version 0.1.3 - July 14, 2026

- Added a compact Kami-style chat layout with responsive HUD positioning and an option to restore the wide vanilla layout.

## Version 0.1.1 - July 14, 2026

- Added native Windows launchers for starting and updating the client.
- Removed PowerShell and command scripts from the distributed friends package.
- Added secure update downloads with SHA-256 verification and safe version activation.
- Bundled the required Java runtime so users do not need to install Java separately.

## Version 0.1.0 - July 14, 2026

- Published the first shareable Haven Client release.
- Added automatic updates through GitHub Releases.
- Included custom client options, interface improvements, radius toggles, and configurable keybindings.
- Added Auto Pick Bark and Chip Boulder automation with shared pathfinding safety features.
