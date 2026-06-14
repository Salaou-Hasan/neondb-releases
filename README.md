# NeonDB Releases

Download the latest binary from the [Releases page](https://github.com/Salaou-Hasan/neondb-releases/releases/latest).

---

## Install — Windows (x86_64)

Run both lines in PowerShell (the first forces TLS 1.2, required by GitHub):

```powershell
[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12
Invoke-WebRequest -Uri "https://github.com/Salaou-Hasan/neondb-releases/releases/latest/download/neondb-windows-x86_64.exe" -OutFile "neondb.exe"
```

Then move `neondb.exe` somewhere on your PATH (e.g. `C:\Windows\System32\`) or run it from your project folder.

---

## Install — Linux / macOS

Coming soon.

---

## Quick start

```
neondb init
neondb start
neondb update
```

Source code: https://github.com/Salaou-Hasan/NeonDB