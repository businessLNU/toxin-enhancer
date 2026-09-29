# Toxin Enhancer — Keep Your MacBook Awake with the Lid Closed (Clamshell Mode) on Battery

**Toxin Enhancer** lets your Mac stay awake with the **display closed (clamshell mode)**
even **on battery** — no external monitor, keyboard, or power adapter required. It is the
free companion to [**Toxin**](https://toxin-app.com), the lightweight macOS menu-bar app that
keeps your Mac awake and prevents sleep.

> Keywords: keep Mac awake, prevent Mac from sleeping, keep MacBook awake with lid closed,
> clamshell mode on battery, disable sleep macOS, caffeine / Amphetamine alternative,
> keep display awake, stop Mac sleeping when closed.

## What it does

macOS normally sleeps as soon as you close the lid unless the Mac is plugged in and driving an
external display. **Toxin** already keeps your Mac awake with the lid closed **while on power**,
with zero setup. **Toxin Enhancer** extends that to **battery power**, which macOS only permits
after a one-time administrator setup (`pmset disablesleep`).

A sandboxed Mac App Store app is not allowed to make that system-level change, so the Enhancer
is distributed here separately — the same approach [Amphetamine](https://apps.apple.com/app/amphetamine/id937984704)
uses with its "Amphetamine Enhancer". Install it once and Toxin handles the rest.

## Features

- ✅ Keep your **MacBook awake with the lid closed** on battery (true clamshell mode)
- ✅ Works together with Toxin's menu-bar toggle — no extra app to keep running
- ✅ **Signed with Apple Developer ID and notarized by Apple** — opens without Gatekeeper warnings
- ✅ One-time setup, one admin password prompt
- ✅ Fully removable at any time
- ✅ **No data collection**, no tracking, no account

## Download & install

1. Download **`Toxin-Enhancer.dmg`** from the [**latest release**](../../releases/latest).
2. Open the DMG and drag **Toxin Enhancer** into your **Applications** folder.
3. Launch it, click **Install**, and enter your admin password once.
4. Quit the Enhancer. In Toxin, turn on **"Prevent sleep when the display is closed"** — it now
   works on battery too.

## How to uninstall

Open Toxin Enhancer again and click **Remove**. This deletes the helper script and the
`sudoers` rule it created, restoring the default macOS sleep behavior.

## Requirements

- macOS 13 (Ventura) or later
- Apple Silicon or Intel Mac
- The [Toxin](https://toxin-app.com) app (free on the Mac App Store)

## FAQ

**How do I keep my MacBook awake with the lid closed without an external monitor?**
Install Toxin plus Toxin Enhancer, then enable "Prevent sleep when the display is closed" in
Toxin. No external display, keyboard, or mouse is needed.

**Does it work on battery?**
Yes — that is exactly what the Enhancer adds. Toxin alone covers closed-lid on power; the
Enhancer covers battery.

**Is it safe?**
Yes. It is signed with an Apple Developer ID and notarized by Apple, collects no data, and can
be fully removed with one click.

**Why isn't this on the Mac App Store?**
App Store apps are sandboxed and cannot change the system sleep policy required for
closed-display mode on battery. This companion app performs that one-time setup outside the
sandbox.

**Is it a free Amphetamine or Caffeine alternative?**
Toxin is a modern, lightweight menu-bar app to keep your Mac awake and prevent sleep, with an
optional closed-display mode via this Enhancer.

## Related

- [Toxin — Keep Your Mac Awake (Mac App Store)](https://toxin-app.com)
- Website: https://toxin-app.com/enhancer

---

© PF Capital Management UG. Toxin Enhancer is a free companion utility for Toxin.
