# Dev Changelog

## 2026-03-28

- Added Midnight-safe helper decisions for secret health and power handling.
- Reworked health text to avoid secret-derived autosizing and to use native safe health APIs where possible.
- Reworked power text to degrade safely when power values are secret.
- Updated Midnight shield indicator handling to use native bar semantics instead of unsafe local percentage math.
- Added a dual-path Midnight dispel flow:
  - general harmful aura scan remains for normal debuff systems
  - dedicated dispellable aura scan now feeds dispel visibility and dispellable-only filtering

## 2026-03-29

- Updated retail dispel type icons to use Blizzard's current raid-frame atlases with fallback to Cell's local textures.
