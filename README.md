# Saghro Trek

An offline endless trail-runner set in Morocco's Jbel Saghro. You run from Tagdilt over the
passes, past the rock towers of Bab n'Ali, down to N'Kob and on into the desert.
Your pack mule follows close behind.

Everything is in `index.html`: no network, no dependencies, no build step.

## Play

| | Keyboard | Touch |
|---|---|---|
| Jump (hold = higher) | Space / ↑ / W | Tap the right side |
| Double jump | Press again in mid-air | Tap again |
| Duck / fast-fall | ↓ / S | Hold the left side |
| Pause | P / Esc | ⏸ button |
| Sound | M | 🔈 button |

- **Dates** are worth +10 points.
- **Water** runs down all the time. Grab bottles or the trek ends.
- **Mint tea** makes you invincible for a few seconds and smashes whatever you run into.
- Every **waypoint** you reach gives +100. You can take 3 tumbles.
- The run speeds up over time and cycles through day and night. The scenery changes by
  region: mountains, rock towers, oasis, then dunes.

Your best score is saved in the browser.

## Getting it onto a device before the flight

- **Laptop:** download `index.html` and open it in any browser. It works fully offline.
- **Phone:** turn on GitHub Pages for this repo (Settings → Pages → deploy from branch).
  Open the page once while you're online, then use *Add to Home Screen*. A service worker
  (`sw.js`) caches the game, so it launches offline.
- **Phone (Android):** you can also save `index.html` to the device and open it from a
  file manager in Chrome.

The waypoint names and distances are set in `WAYPOINTS` near the top of the script.
Edit them to match the route you actually walked.
