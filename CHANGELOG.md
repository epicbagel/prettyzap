# Changelog

All notable PrettyZap and Omarchy plugin changes are documented here.

## [0.2.6] - 2026-08-26

### Added

- Added a `Hide badge` / `Show badge` action to the Omarchy PrettyZap control
  panel. This controls the unread-count badge independently from notification
  permissions and persists across restarts.
- Added the `ToggleBadge` app action and matching plugin integration so the
  control panel always reflects the current badge state.
- Made the active Omarchy tray icon use the configured accent color instead of
  a fixed blue color.

### Fixed

- Kept the emoji picker and native composer menus within the expanded drawer
  bounds so their edge content is not clipped.

### Packaging

- Published the Linux AppImage release artifact and updated the
  `prettyzap-bin` AUR package to version `0.2.6`.
