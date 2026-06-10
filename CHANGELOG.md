# Changelog

All notable changes to the Maca desktop app are documented here. The latest
build is always available at:
https://github.com/crafter-station/maca-releases/releases/latest/download/Maca-arm64.dmg

Maca uses `0.0.x` patch versions during early development and follows
[Keep a Changelog](https://keepachangelog.com/) conventions.

## [Unreleased]

- Auth: collapse the token + subscription "refresh storm" with
  stale-while-revalidate guards, fixing unexpected sign-outs and slow
  subscription checks.

## [0.0.55]

- Fix: "Restart & Update" now fully terminates before ShipIt swaps the app,
  avoiding a stuck updater on some machines.

---

Entries before 0.0.55 were not tracked in this changelog. See the
[releases page](https://github.com/crafter-station/maca-releases/releases) for
the full version history going forward.
