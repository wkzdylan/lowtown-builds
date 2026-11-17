# Lowtown builds

Builds of **Lowtown**, a low-poly open-world crime sandbox: Calder Bay, a harbour city with traffic, people, police, jobs and shops,
played in third person alone or online with friends.

## Downloads

Each release `v<version>` carries:

| File | What it is |
|---|---|
| `Lowtown-<version>-win64.zip` | The game for Windows 10/11, 64-bit. Unzip and run `Lowtown.exe`. |
| `Lowtown-<version>-linux-x86_64.zip` | The game for Linux and the Steam Deck. Unzip and run `Lowtown.x86_64`. |
| `Lowtown-Server-<version>-linux-arm64.zip` | The dedicated server for Linux on ARM64, as the Pelican egg installs it. |

Players and the server need the same version.

## versions.json

The list of builds, written by the game's `tools/publish_build.py`: version, channel, tag, files with size and SHA-256. The Pelican
egg (`tools/pelican` in the game) reads it to install and update a server. Don't edit it by hand.
