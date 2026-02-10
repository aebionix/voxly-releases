# CLAUDE.md - voxly-releases

## Voxly Projekt-Struktur (WICHTIG!)

**Voxly besteht aus drei separaten Repositories/Verzeichnissen:**

| Verzeichnis | Zweck | GitHub Repo | Zugriff |
|-------------|-------|-------------|---------|
| **X:\Wisper** | Source Code, Development | github.com/aebionix/Wisper | Privat |
| **X:\voxly-releases** | Releases, update-info.json | github.com/aebionix/voxly-releases | Öffentlich |
| **X:\voxly-website** | Website (index.html) | github.com/aebionix/voxly-website | Öffentlich |

## Dieses Repo (voxly-releases)

**Zweck:** Öffentliches Releases-Repo für Voxly

**Inhalt:**
- GitHub Releases mit Installer-Dateien
- `update-info.json` - Auto-Update Manifest
- README mit Download-Links

**Workflow:**
1. Releases werden automatisch von `X:\Wisper\release.ps1` erstellt
2. Installer + update-info.json werden hierher gepusht
3. GitHub Release wird mit `gh release create` erstellt

**NIEMALS:** Source Code oder sensible Daten hier pushen!

## Andere Repos

- **Source Code:** `X:\Wisper`
- **Website:** `X:\voxly-website`
