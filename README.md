# qbittorrent-windows-arm
[qBittorrent](https://github.com/qbittorrent/qBittorrent) is a bittorrent client programmed in C++ / Qt that uses libtorrent. The goal of this repository is to build qBittorrent for Windows on ARM (WinRT).

Please go to [releases](https://github.com/gailium119/qbittorrent-windows-arm/releases) for the latest binary files.

## How to build

### Cross compile on Windows x64

This is the way we release qBittorrent for Windows on ARM. A [workflow file](https://github.com/gailium119/qbittorrent-windows-arm/blob/main/.github/workflows/ci_windows_arm.yaml) is written to automatically build with Github actions.
