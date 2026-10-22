# Mapseek Loom

Public static build of Mapseek Loom. This repository contains deployment artifacts only.

Website: https://mapseekai.github.io/mapseek-loom-web/

Current build: [static-2026-10-22-r2](https://github.com/mapseekai/mapseek-loom-web/releases/tag/static-2026-10-22-r2), from source commit `bd919ad47d52b42a30f092ac61d20145b70768aa`, using EMap 0.15.0. This build fixes geometry Worker loading for large layers and handles superseded basemap requests.

Download the static ZIP from Releases, extract it, and serve its contents over HTTPS or localhost. No application backend is required. Hash routes and relative asset URLs support subdirectory hosting.

Projects remain in your browser storage. Use .msk exports to back up or transfer projects between sites. External basemaps and optional GIS resources require an internet connection.
