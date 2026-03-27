# Changelog

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
