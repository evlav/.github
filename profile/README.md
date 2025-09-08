# evlaV 2.0

[Evlav](https://gitlab.com/evlaV) was an automatically generated mirror of SteamOS repositories built from the Arch package sources Valve [provides](https://steamdeck-packages.steamos.cloud/archlinux-mirror/sources) to comply with various open source licenses. It was also the home to some interesting lore. Starting in August 6th, 2025, it shuttered, which prompted the creation of this replacement.

This successor features a completely rebuilt [integration tool](https://github.com/evlav/evlav) that automatically rebuilds the SteamOS Holo and Jupiter repositories and syncs individual branches (e.g., `3.5`, `3.6`) with branch point calculation. So, when going to those branches, you can see where they split from the `main` SteamOS branch. The dates are also correct, so you can see when each update happened.

To be respectful to the environment, it runs in seconds when there are no new updates and only downloads index files (a few kb). It is also bandwidth sparing (packages are only downloaded once). This allows it to run four times per day without affecting the upstream mirror.
