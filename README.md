# Anime Solution updates

Official public update feed and verified Windows releases for **Anime Solution (AniSol)**.

AniSol itself is a native C++/Qt application. `update.json` is not application code; it is a small machine-readable manifest that tells the compiled C++ updater which version and package are current. Keeping the manifest separate lets an installed app discover a future release without recompiling itself first.

- [Latest release](https://github.com/RealNumNums/anisol-updates/releases/latest)
- [Live update manifest](https://raw.githubusercontent.com/RealNumNums/anisol-updates/main/update.json)

Packages are checked against their exact byte size and SHA-256 digest before the external C++ launcher can install them. Installation remains an explicit user action and failed launches roll back automatically.