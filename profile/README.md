# Evlav 2.0
## now with 95% less schizoposting

[Evlav](https://gitlab.com/evlaV) was an automatically generated mirror of SteamOS repositories built from the Arch package sources Valve [provides](https://steamdeck-packages.steamos.cloud/archlinux-mirror/sources) to comply with various open source licenses. It was also the home to some interesting lore. Starting in August 6th, 2025, it shuttered, which prompted the creation of this replacement.

This successor features a completely rebuilt [integration tool](https://github.com/evlav/evlav) that automatically rebuilds the Holo and Jupiter repositories and supports syncing individual branches (e.g., 3.5, 3.6) with branch point calculation. So, when going to those branches, you can see where they split from the `main` SteamOS branch. The dates are also correct, so you can see when each update happened.

To be respectful to the environment, it also runs in seconds when there are no new updates only downloading index files (a few kb), and is bandwidth sparing (packages are only downloaded once). This allows it to run multiple times a day without affecting the upstream mirror.
