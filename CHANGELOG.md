# Changelog

## v0.1.0-alpha.4

## What's Changed

* fix: expand hint bar to fill window when no projects exist
* fix: prevent panel shrinking on horizontal scroll
* feat: confirm before quitting the app
* fix: batch addProject store mutations to prevent panel re-show
* feat: align app theme with marketing page
* feat: replace app icon with themed layers icon
* feat: add native context menu for browser panels
* fix: make single panel use full width instead of half
* feat: browser panel DevTools
* feat: auto-create terminal when switching to empty row
* feat: clickable PR numbers and GitHub repo link in sidebar
* fix: polish landing page
* feat: add OG image and social meta tags
* feat: show site favicon in browser panel chrome strip


## v0.1.0-alpha.3

## What's Changed

* fix: restrict Linux release builds to runner's own architecture
* fix: resolve user PATH at startup so gh CLI works in packaged app
* fix: use boolean arch flags for electron-builder CLI


## v0.1.0-alpha.2

## What's Changed
* fix: spawn terminal as login shell for correct PATH by @joseph-lozano in https://github.com/joseph-lozano/flywheel/pull/38
* ci: skip macOS build on draft PRs by @joseph-lozano in https://github.com/joseph-lozano/flywheel/pull/42
* fix: use store predicate paths so sidebar reflects branch renames by @joseph-lozano in https://github.com/joseph-lozano/flywheel/pull/41
* fix: skip closed PR worktrees during discovery by @joseph-lozano in https://github.com/joseph-lozano/flywheel/pull/44
* release: v0.1.0-alpha.2 by @joseph-lozano in https://github.com/joseph-lozano/flywheel/pull/45


**Full Changelog**: https://github.com/joseph-lozano/flywheel/compare/v0.1.0-alpha.1...v0.1.0-alpha.2


## v0.1.0-alpha.1

Initial alpha release of Flywheel — a tiling terminal workspace built on Electron.

### Highlights
- Tiling layout with terminal and browser panels
- Multi-project sidebar with git worktree support
- PR status icons in worktree sidebar
- Per-panel zoom and cascading YAML config
- In-app browser via BROWSER env var interception
- Signed macOS DMG with auto-update
- Linux AppImage and deb packages (x64 + arm64)
