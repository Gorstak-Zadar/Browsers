# 🌐 Browsers

> PowerShell script to apply **privacy and security settings** to Chromium-based browsers (Chrome, Edge, etc.) — WebRTC, remote desktop, and plugins.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🔒 **WebRTC** | Configures `media_stream` and `webrtc` settings |
| 🖥️ **Remote Desktop** | Disables remote desktop support in browser |
| 🔌 **Plugins** | Disables browser plugins |
| 📋 **JSON Prefs** | Modifies browser `Preferences` files |

---

## 📋 Requirements

| Requirement | Details |
|-------------|---------|
| **OS** | Windows 10/11 |
| **PowerShell** | 5.1+ |
| **Browsers** | Chromium-based (Chrome, Edge, etc.) |

---

## 🚀 Usage

```powershell
.\Browsers.ps1
```

---

## 🔧 What It Does

- Locates browser `Preferences` files under `%LocalAppData%`
- Sets `media_stream = 2`, `webrtc = 2`
- Disables `remote.enabled` and `remote.support`
- Disables all plugins

---

<p align="center">
  <sub>🛡️ Gorstak Privacy Tooling</sub>
</p>
