# Changelog

All notable changes to the Maca desktop app are documented here. The latest
build is always available at:
https://github.com/crafter-station/maca-releases/releases/latest/download/Maca-arm64.dmg

Maca uses `0.0.x` patch versions during early development and follows
[Keep a Changelog](https://keepachangelog.com/) conventions.

## [Unreleased]

## [0.0.63]

- Maca is now open source under the AGPL-3.0 license.
- Safer sign-in: the app only accepts a sign-in it started itself, and your
  session tokens no longer pass through the browser.
- Meeting transcription accepts short-lived access tokens.

## [0.0.62]

- New Transforms: select any text and press Option+1 to polish it in place,
  or Option+2 to turn rough notes into a clear AI prompt. Create up to 8 of
  your own transforms, each with its own shortcut, and press Option+O to see
  what changed, undo, or retry.
- Transforms can also run automatically on every dictation.
- Onboarding now includes a quick Transforms walkthrough.

## [0.0.59]

- Maca now warns you when another app is blocking your keyboard with macOS
  Secure Input, and tells you how to fix it, instead of the shortcut silently
  doing nothing. This was a common cause of "Fn stopped working."
- Fixed hotkeys firing on the wrong key on non-QWERTY keyboard layouts
  (Dvorak, AZERTY, Colemak). Bindings now resolve against your active layout.

## [0.0.57]

- New translate mode: press Shift+Fn to dictate, then tap Fn to insert your
  speech translated into your chosen language. Pick the language in onboarding
  or Settings, and rebind the shortcut anytime under Settings → Shortcuts.

## [0.0.56]

- Fixed unexpected sign-outs and slow subscription checks caused by an
  over-eager background refresh loop (token and subscription refreshes are
  now coalesced and served from cache while still fresh).

## [0.0.55]

- Fix: "Restart & Update" now fully terminates before ShipIt swaps the app,
  avoiding a stuck updater on some machines.

---

Entries before 0.0.55 were not tracked in this changelog. See the
[releases page](https://github.com/crafter-station/maca-releases/releases) for
the full version history going forward.
