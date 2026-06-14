# NeonDB Binaries

Pre-built binaries for NeonDB. Download with one command — no GitHub page needed.

---

## Download

### Windows (x86_64)

**PowerShell:**
```powershell
Invoke-WebRequest -Uri "https://github.com/Salaou-Hasan/neondb-releases/releases/latest/download/neondb-windows-x86_64.exe" -OutFile "neondb.exe"
```

**curl:**
```bash
curl -L -o neondb.exe https://github.com/Salaou-Hasan/neondb-releases/releases/latest/download/neondb-windows-x86_64.exe
```

After downloading, move it somewhere on your PATH (e.g. `C:\Windows\System32\`) or run it from the project folder.

---

### Linux (x86_64)

```bash
curl -L -o neondb https://github.com/Salaou-Hasan/neondb-releases/releases/latest/download/neondb-linux-x86_64
chmod +x neondb
sudo mv neondb /usr/local/bin/
```

---

### macOS (Apple Silicon / ARM64)

```bash
curl -L -o neondb https://github.com/Salaou-Hasan/neondb-releases/releases/latest/download/neondb-macos-arm64
chmod +x neondb
sudo mv neondb /usr/local/bin/
```

### macOS (Intel / x86_64)

```bash
curl -L -o neondb https://github.com/Salaou-Hasan/neondb-releases/releases/latest/download/neondb-macos-x86_64
chmod +x neondb
sudo mv neondb /usr/local/bin/
```

---

## Quick start after installing

```bash
neondb init        # scaffold a new project
neondb start       # start the server
neondb call <reducer> '[args]'
```

Source code: [github.com/Salaou-Hasan/NeonDB](https://github.com/Salaou-Hasan/NeonDB)

---

## Available binaries

| File | Platform | Status |
|---|---|---|
| `neondb-windows-x86_64.exe` | Windows 10/11 x64 | ✅ Available |
| `neondb-linux-x86_64` | Linux x64 (Ubuntu 20.04+) | 🔜 Coming soon |
| `neondb-macos-arm64` | macOS Apple Silicon (M1/M2/M3) | 🔜 Coming soon |
| `neondb-macos-x86_64` | macOS Intel | 🔜 Coming soon |
