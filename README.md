# Hiveflow Desktop for Linux 🐧

[![Latest release](https://img.shields.io/github/v/release/hiveflowai/hiveflow-linux?label=latest&color=blue)](https://github.com/hiveflowai/hiveflow-linux/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/hiveflowai/hiveflow-linux/total?color=green)](https://github.com/hiveflowai/hiveflow-linux/releases)
[![Platform](https://img.shields.io/badge/platform-Linux-FCC624?logo=linux&logoColor=black)](https://github.com/hiveflowai/hiveflow-linux/releases/latest)

Official Linux releases for **Hiveflow Desktop** — the desktop companion for [Hiveflow](https://hiveflow.ai), the visual AI agent orchestrator. Connect your machine to your Hiveflow workspace, run local apps, and automate workflows from your desktop.

> 🌐 Website: [hiveflow.ai](https://hiveflow.ai) · Web app: [app.hiveflow.ai](https://app.hiveflow.ai)

---

## ⬇️ Download

**[Download the latest version →](https://github.com/hiveflowai/hiveflow-linux/releases/latest)**

| File | Description |
|---|---|
| `Hiveflow-Desktop-X.X.X-<arch>.AppImage` | **AppImage (recommended)** — portable, works on most distros, self-updates |
| `hiveflow-desktop-app_X.X.X_<arch>.deb` | Debian/Ubuntu package |

> ℹ️ Current builds target **arm64**. x64 builds are on the roadmap — if you need x64 today, [open an issue](https://github.com/hiveflowai/hiveflow-linux/issues) to let us know.

## 🔧 Installation

### AppImage (recommended)

```bash
chmod +x Hiveflow-Desktop-*.AppImage
./Hiveflow-Desktop-*.AppImage
```

### Debian / Ubuntu (.deb)

```bash
sudo apt install ./hiveflow-desktop-app_*.deb
# or: sudo dpkg -i hiveflow-desktop-app_*.deb && sudo apt -f install
```

Then launch **Hiveflow Desktop** and sign in with your Hiveflow account.

## 🔄 Automatic updates

The **AppImage** checks for updates automatically. For `.deb` installs, download new versions from this page.

## 💻 System requirements

- A modern Linux distribution (Ubuntu 20.04+, Debian 11+, Fedora 36+, Arch, etc.)
- glibc 2.31+ · FUSE for AppImage (preinstalled on most distros)

## 📦 Looking for another OS?

| Platform | Repository |
|---|---|
| 🪟 **Windows** (installer / portable) | [hiveflowai/hiveflow-windows](https://github.com/hiveflowai/hiveflow-windows/releases/latest) |
| 🍎 **macOS** (Apple Silicon + Intel) | [hiveflowai/hiveflow-mac-os](https://github.com/hiveflowai/hiveflow-mac-os/releases/latest) |

---

## 🇪🇸 Español

**Hiveflow Desktop para Linux** — la app de escritorio de [Hiveflow](https://hiveflow.ai), el orquestador visual de agentes de IA.

**Instalación (AppImage, recomendado):**

```bash
chmod +x Hiveflow-Desktop-*.AppImage
./Hiveflow-Desktop-*.AppImage
```

**Debian/Ubuntu:** `sudo apt install ./hiveflow-desktop-app_*.deb`

El AppImage se **actualiza solo**. Los builds actuales son **arm64** (x64 en el roadmap). ¿Buscas otra plataforma? Arriba está la tabla con **Windows** y **macOS**.

---

© Hiveflow, Inc. · [hiveflow.ai](https://hiveflow.ai)
