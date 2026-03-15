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

---

## Disclaimer

**NO WARRANTY.** THERE IS NO WARRANTY FOR THE PROGRAM, TO THE EXTENT PERMITTED BY APPLICABLE LAW. EXCEPT WHEN OTHERWISE STATED IN WRITING THE COPYRIGHT HOLDERS AND/OR OTHER PARTIES PROVIDE THE PROGRAM "AS IS" WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESSED OR IMPLIED, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE. THE ENTIRE RISK AS TO THE QUALITY AND PERFORMANCE OF THE PROGRAM IS WITH YOU. SHOULD THE PROGRAM PROVE DEFECTIVE, YOU ASSUME THE COST OF ALL NECESSARY SERVICING, REPAIR OR CORRECTION.

**Limitation of Liability.** IN NO EVENT UNLESS REQUIRED BY APPLICABLE LAW OR AGREED TO IN WRITING WILL ANY COPYRIGHT HOLDER, OR ANY OTHER PARTY WHO MODIFIES AND/OR CONVEYS THE PROGRAM AS PERMITTED ABOVE, BE LIABLE TO YOU FOR DAMAGES, INCLUDING ANY GENERAL, SPECIAL, INCIDENTAL OR CONSEQUENTIAL DAMAGES ARISING OUT OF THE USE OR INABILITY TO USE THE PROGRAM (INCLUDING BUT NOT LIMITED TO LOSS OF DATA OR DATA BEING RENDERED INACCURATE OR LOSSES SUSTAINED BY YOU OR THIRD PARTIES OR A FAILURE OF THE PROGRAM TO OPERATE WITH ANY OTHER PROGRAMS), EVEN IF SUCH HOLDER OR OTHER PARTY HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGES.
