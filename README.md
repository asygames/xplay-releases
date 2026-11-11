# XPLAY — Releases

Public releases of **XPLAY**, a modular game launcher for Linux (Qt Quick) with Minecraft, Roblox, Steam and Epic Games modules. English by default, with Romanian available in Settings.

XPLAY updates itself from these releases. Source code is maintained privately. This repository only holds compiled releases.

## Download

Get `XPlay-<version>-x86_64.AppImage` from the [latest release](../../releases/latest):

```sh
chmod +x XPlay-*-x86_64.AppImage
./XPlay-*-x86_64.AppImage
```

Verify the download with the `.sha256` file published next to it:

```sh
sha256sum -c XPlay-*-x86_64.AppImage.sha256
```

Requires a desktop and a graphics driver, and glibc 2.43 or newer (built on Ubuntu 26.04). Java for Minecraft is downloaded by the launcher. Steam games need the Steam client installed; Epic Games titles and Roblox Studio run through Proton.

Not affiliated with Mojang, Roblox Corporation, Valve or Epic Games.
