# Bluetm scoop-bucket

Scoop bucket for [Bluetm.uz](https://github.com/Azizbek16l) OSINT tools.

## Install

```powershell
scoop bucket add bluetm https://github.com/Azizbek16l/scoop-bucket
scoop install mytools-osint
```

After install you get two commands on PATH:
- `osint` — the CLI (`osint github.com --profile red-team --html report.html`)
- `mytools-osint` — the PySide6 GUI

## What's here

| Manifest | Description |
|----------|-------------|
| `mytools-osint` | Personal OSINT CLI + GUI — 24 modules, free APIs, red-team profiles |

## Update

```powershell
scoop update
scoop update mytools-osint
```
