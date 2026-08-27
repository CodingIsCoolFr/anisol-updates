# Anime Solution downloads and updates

Official public download and update feed for **Anime Solution (AniSol)**. The
application source and verified Windows builds are published separately so
existing installations can always update from a small, stable public feed.

AniSol itself is a native C++/Qt application. `update.json` is not application code; it is a small machine-readable manifest that tells the compiled C++ updater which version and package are current. Keeping the manifest separate lets an installed app discover a future release without recompiling itself first.

- [Download the latest Windows installer](https://github.com/CodingIsCoolFr/anisol-updates/releases/latest/download/Anime-Solution-Setup-0.11.60-win64.exe)
- [Latest release and checksums](https://github.com/CodingIsCoolFr/anisol-updates/releases/latest)
- [Live update manifest](https://raw.githubusercontent.com/CodingIsCoolFr/anisol-updates/main/update.json)

Packages are checked against their exact byte size and SHA-256 digest before the external C++ launcher can install them. AniSol can install automatically only after playback has stopped and its window is minimized; users can also choose **Update & restart** directly. Failed launches roll back automatically.
