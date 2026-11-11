# Vartex: free F1 25 telemetry overlays for Windows

**F1 overlays you can read while driving.** Inputs, tyre wear, your lap delta and the cars beside you, drawn over F1 25.

Free for Windows 10 and 11. No account required.

**[Download Vartex](https://vartex.app/api/updater/download/latest)** · [Website](https://vartex.app) · [Discord](https://discord.gg/MxWzqzy2Wk)

## Overlays

- **[Input Graph](https://vartex.app/overlays/input-graph):** how your steering, throttle and braking change through each corner.
- **[Tyre Management](https://vartex.app/overlays/tyre-management):** the wear through a stint, and how many laps each tyre has left.
- **[Delta](https://vartex.app/overlays/delta):** the time you gain or lose against your best lap, at the same point on track.
- **[Radar](https://vartex.app/overlays/radar):** the cars around you from above, with a red warning while one is alongside.

## Why Vartex

- **Made for the F1 games.** Each overlay is built around the data these games send. There is no dashboard to design and no plugin to install.
- **Native and light.** A Windows app written in Rust that draws with the GPU, not a web page in a browser window. An overlay redraws only when new data arrives.
- **Nothing touches the game.** Vartex only listens for the UDP telemetry the game sends on purpose. It installs no mods, changes no files and injects nothing.
- **Set up from the game.** Press F6 during a session to drag every overlay where you want it. Each one has a preview with sample data and can hide while you pause.
- **Keeps your other apps working.** If you also run SimHub or Crew Chief, Vartex passes every packet on to them unchanged.

## Get started

1. Install Vartex.
2. In the game's telemetry settings: **UDP Telemetry** On, **UDP Port** 20777, **UDP Send Rate** 60 Hz.
3. Start a session. Your overlays appear as soon as data arrives.

What each value does, and what to do when nothing arrives: [F1 25 and F1 26 UDP telemetry settings](https://vartex.app/guides/f1-25-udp-telemetry-settings).

Works with F1 23, F1 24, F1 25 and its 2026 Season Pack.

## Community

- **Discord:** [discord.gg/MxWzqzy2Wk](https://discord.gg/MxWzqzy2Wk)
- **Support development:** [buymeacoffee.com/vartexapp](https://www.buymeacoffee.com/vartexapp)
