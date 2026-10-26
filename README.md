# 2.20-Map-Files

Map files for Helbreath 2.20, one folder per map.

## Contents

- `maps/<map>/<map>.amd` - the raw map file shipped with the retail 2.02 client (`MAPDATA`).
- `maps/<map>/<map>.txt` - the game server's map-info file (spawns, teleports, zones) from the 2.20 server import.
- `maps/<map>/server/<map>.amd` - present only where the server's copy differs from the client's.

A human-readable breakdown of each `.amd` is planned (a converter still has to be written; see the project board).

## Branches

| Branch | Purpose |
|---|---|
| `original` | The files exactly as found. Read-only by convention: never commit here. (It is not protected yet, because the org is on GitHub Free and its repos are private.) |
| `development` | Integration branch. Work happens in feature branches, which merge into `development`. |
| `stable` | Default branch. `development` is merged here once it is stable. |

## Project

Part of [Original Helbreath](https://github.com/Original-Helbreath): keeping the original 1999-2005 Siementech Helbreath alive.
Repos are named `<version>-<Part>`; other versions follow the same pattern.
Issues are tracked on the [project board](https://github.com/Original-Helbreath/projects/1). The analysis behind everything is in
[2.20-Documentation](https://github.com/Original-Helbreath/2.20-Documentation).
