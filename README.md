# Turmoil client releases

Release artifacts for the Turmoil client. Binaries are published as GitHub Release assets.

Download [launcher.jar](https://github.com/dmndmedia1/turmoil-client-releases/releases/download/production/launcher.jar)
and run it with Java 8 or newer. The launcher installs its Java 21 game runtime,
downloads the current client, and checks its SHA-256 before launching it.

The [production release](https://github.com/dmndmedia1/turmoil-client-releases/releases/tag/production)
contains `client.jar`, `client.sha256`, `launcher.jar`, and `launcher.sha256`.
Each checksum file contains the SHA-256 of its matching JAR.

The root `client.jar` is stored using Git LFS because of its size. Release downloads
are ordinary JAR files and do not require Git LFS. This repository contains release
artifacts only; source code and private build reports are not published here.
