# NeonDB Binaries

Pre-built binaries committed directly to this repo — download with one command, no browser needed.

## Install

### Windows (x86_64)

PowerShell:

    Invoke-WebRequest -Uri "https://raw.githubusercontent.com/Salaou-Hasan/neondb-releases/main/windows/neondb-windows-x86_64.exe" -OutFile "neondb.exe"

Move neondb.exe somewhere on your PATH (e.g. C:\Windows\System32\) or run it from your project folder.

### Linux (x86_64) - coming soon

    curl -L -o neondb https://raw.githubusercontent.com/Salaou-Hasan/neondb-releases/main/linux/neondb-linux-x86_64
    chmod +x neondb && sudo mv neondb /usr/local/bin/

### macOS (Apple Silicon) - coming soon

    curl -L -o neondb https://raw.githubusercontent.com/Salaou-Hasan/neondb-releases/main/macos/neondb-macos-arm64
    chmod +x neondb && sudo mv neondb /usr/local/bin/

## Quick start

    neondb init
    neondb start
    neondb call <reducer> [args]

Source code: https://github.com/Salaou-Hasan/NeonDB

## Binaries in this repo

    windows/neondb-windows-x86_64.exe  - Windows 10/11 x64       - Available
    linux/neondb-linux-x86_64          - Linux x64                - Coming soon
    macos/neondb-macos-arm64           - macOS Apple Silicon      - Coming soon
