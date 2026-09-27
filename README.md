# Unfold downloads

Test builds of [Unfold](https://unfold-planner.vercel.app), a to-do list and calendar for time blocking,
with Hyperfocus sessions. This repository only holds the files; the code lives elsewhere.

- **macOS 14 or later** (Apple silicon and Intel): download
  [Unfold.dmg](https://github.com/nemira-labs/unfold-releases/releases/latest/download/Unfold.dmg), open
  it, and drag Unfold to Applications. It's signed with Developer ID and notarized by Apple.
- **Omarchy** (Arch Linux, x86_64):

  ```sh
  curl -fsSL https://unfold-planner.vercel.app/install.sh | bash
  unfold-omarchy-setup --apply   # keys, bar module and theme hook; run it without --apply to preview
  ```

  The [script](https://unfold-planner.vercel.app/install.sh) downloads
  `unfold-omarchy-x86_64.pkg.tar.zst` from the latest release and installs it with `pacman -U`. Run it
  again to update; remove Unfold with `sudo pacman -R unfold-omarchy`.

Every version is on the [releases page](https://github.com/nemira-labs/unfold-releases/releases).
