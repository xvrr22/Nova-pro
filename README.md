# 🚀 NOVA PRO ULTIMATE — BAZZITE INSTALLATION GUIDE

Welcome to NOVA Pro Ultimate, a customizable gaming control center designed for Bazzite Linux.

## ✨ Features

- Dashboard with system and app status
- Customizable themes, colors, and interface
- Gaming profiles and editable presets
- Performance preferences and diagnostic tools
- Settings import and export
- Sober compatibility checks for Roblox
- Quick access to configuration folders and logs
- Easy application-menu launcher
- Local settings and backups

**Important:** Performance readings must come from real system data. Profiles save your preferences and do not automatically guarantee higher FPS.

## 📦 Installation

### Step 1 — Extract the ZIP

Download the NOVA Pro Ultimate ZIP and extract it using your file manager.

Open a terminal in the extracted `NOVA_Pro_Ultimate` folder.

### Step 2 — Install NOVA Pro

Run these commands one at a time:

```bash
chmod +x install.sh
./install.sh
```

The installer should copy the application files into your local user directory and create a launcher.

### Step 3 — Launch the application

Open your applications menu and search for **NOVA Pro Ultimate**.

Alternatively, run:

```bash
~/.local/bin/nova-pro
```

### Step 4 — Customize your setup

Inside NOVA Pro, configure your theme, accent color, gaming preferences, and profiles. Save your settings and export a backup so you can restore them later.

## 🛠️ Troubleshooting

**Launcher not found:**

```bash
ls -la ~/.local/bin/nova-pro
```

**Application files missing:**

```bash
ls -la ~/.local/share/nova-pro/
```

**Check whether Sober is installed:**

```bash
flatpak list | grep -i sober
```

**Check Python:**

```bash
python3 --version
```

The updated browser-based edition should not require Tkinter.

## 🔒 Safety and privacy

NOVA Pro should not require administrator permissions for ordinary settings, should not silently change system files, and should never display fake performance readings. Back up configurations before making changes.

Enjoy NOVA Pro Ultimate and customize your gaming setup! 🎮
