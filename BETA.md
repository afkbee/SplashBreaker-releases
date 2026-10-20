# SplashBreaker beta: tester guide

Thanks for testing! SplashBreaker runs many separate browser tiles in one window and
alerts you the moment one gets through a waiting room. This beta is about finding
anything that breaks, confuses you or feels slow.

## 1. Install (5 minutes)

1. Open https://github.com/afkbee/SplashBreaker-releases/releases and find the newest
   **beta** release (it says *Pre-release*).
2. Download **`SplashBreaker-Setup-<version>.exe`** and run it.
3. The app isn't code-signed yet, so you'll see warnings:
   - Chrome: choose **Keep**.
   - Windows "protected your PC": click **More info → Run anyway**.
   - If Windows says *"An Application Control policy has blocked this file"*, Smart App
     Control is on and won't allow unsigned apps. Tell us; don't turn it off for this.

Beta copies update themselves to newer betas, and then to the final release.

## 2. Before your first drop

- Press **Test alert** (on the start screen). You should hear the alarm and see a Windows
  notification. No notification? Turn off Windows **Do Not Disturb**.
- Press **F1** for the guide and shortcuts.

## 3. What to try

- A real drop or waiting room, with as many tiles as your PC handles. Watch the RAM
  figure; tell us your tile count, RAM and how it felt.
- The moment a tile passes: the green bar, **F8** to open it, **F9** to silence, logging
  in and checking out inside the tile.
- Anything a normal person might do: lots of clicking, resizing, minimizing, sleep and
  wake, unplugging a monitor, closing the laptop lid.

## 4. Reporting a problem

1. In SplashBreaker open **Settings** (sliders icon) → **Diagnostics** → **Copy diagnostics**.
2. Paste that into your message, with:
   - what you were doing,
   - what you expected,
   - what happened (a screenshot helps).

The diagnostics contain versions, your PC's memory, tile counts and a short event log.
They never include web addresses, queue IDs, passwords or anything you typed.

## Good to know

- Every tile is a fresh, separate visitor. Sessions are never saved: closing the app ends them.
- All tiles share your internet connection. If a site shows **Error 1015** or "rate
  limited", raise **Stagger** in Settings or run fewer tiles.
- Check each site's rules; some don't allow holding several places in a queue.
