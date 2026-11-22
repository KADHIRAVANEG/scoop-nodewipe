<div align="center">

  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/KADHIRAVANEG/nodewipe/main/assets/logo-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/KADHIRAVANEG/nodewipe/main/assets/logo-light.svg">
    <img alt="nodewipe" src="https://raw.githubusercontent.com/KADHIRAVANEG/nodewipe/main/assets/logo-dark.svg" width="320">
  </picture>

  <br><br>

  **Official Scoop Bucket for [nodewipe](https://github.com/KADHIRAVANEG/nodewipe)**  
  *The surgical, blazing-fast dev-environment cleaner written in Rust.*

  <br>

  [![Scoop](https://img.shields.io/badge/Scoop-v0.9.9-4a90e2?style=for-the-badge&logo=powershell&logoColor=white)](https://github.com/KADHIRAVANEG/scoop-nodewipe)
  [![Release](https://img.shields.io/github/v/release/KADHIRAVANEG/nodewipe?style=for-the-badge&color=8b5cf6&logo=github)](https://github.com/KADHIRAVANEG/nodewipe/releases)
  [![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](https://github.com/KADHIRAVANEG/nodewipe/blob/main/LICENSE)

  <br><br>

  <a href="https://github.com/KADHIRAVANEG/nodewipe">
    <img src="https://raw.githubusercontent.com/KADHIRAVANEG/nodewipe/main/docs/media/nodewipe-demo.gif" alt="nodewipe authentic terminal, TUI, and GUI showcase demo" width="860">
  </a>

</div>

<br>

## Installation via Scoop (Windows)

### Option 1: Add Bucket and Install (Recommended)
```powershell
scoop bucket add nodewipe https://github.com/KADHIRAVANEG/scoop-nodewipe
scoop install nodewipe
```

### Option 2: Direct Manifest Installation
```powershell
scoop install https://raw.githubusercontent.com/KADHIRAVANEG/nodewipe/main/packaging/scoop/nodewipe.json
```

## Updating
```powershell
scoop update nodewipe
```

## Quick Start
```powershell
# Scan and identify reclaimable dev artifacts across 39+ ecosystems
nodewipe scan

# Launch interactive terminal TUI with dry-run mode
nodewipe

# Run system-wide storage analysis across all toolchains
nodewipe doctor C:\Users\<Username>\Projects
```

---

> [!NOTE]
> For complete documentation, architecture deep dive, benchmarks, and Tauri desktop app, visit the main repository:  
> **[github.com/KADHIRAVANEG/nodewipe](https://github.com/KADHIRAVANEG/nodewipe)**
