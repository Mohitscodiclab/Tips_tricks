# 🎵 Ad-Free Spotify Setup Guide (BlockTheSpot)

> This guide helps you set up **ad-free Spotify** on Windows using the [BlockTheSpot](https://github.com/mrpond/BlockTheSpot) script.  
> 🟢 Works with Spotify **downloaded from the official website**.  
> 🔴 Does NOT work with Microsoft Store version.

---

## 🚀 What is BlockTheSpot?

BlockTheSpot is a **PowerShell-based patch** that removes ads from Spotify, while keeping all other functionality intact — including logging in with your account and syncing playlists.

---

## ✅ Prerequisites

- ✅ Windows 10 or 11
- ✅ Installed **Spotify from the official website**:  
  [https://www.spotify.com/download](https://www.spotify.com/download)
- ❌ Uninstall Microsoft Store version if you have it

---

## 🛠️ Installation Steps

### 1. Uninstall Microsoft Store version (if installed)

If you already have Spotify from the **Microsoft Store**, uninstall it:

1. Open **Start Menu** → Search for `Spotify`
2. Right-click → **Uninstall**

---

### 2. Download Spotify from the Official Website

1. Go to [https://www.spotify.com/download](https://www.spotify.com/download)
2. Download and install Spotify

---

### 3. Login to Your Spotify Account

- Open Spotify
- Log in with your account
- Close Spotify completely (make sure it's not running in the background)

---

### 4. Run BlockTheSpot Script in PowerShell

#### 🔹 Open PowerShell as Administrator

1. Press `Win + X` → Select **Windows PowerShell (Admin)**  
   _or search for PowerShell, right-click → Run as administrator_

#### 🔹 Paste and Run the Script Below:

```powershell
[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12; Invoke-Expression "& { $(Invoke-WebRequest -UseBasicParsing 'https://raw.githubusercontent.com/mrpond/BlockTheSpot/master/install.ps1') } -UninstallSpotifyStoreEdition -UpdateSpotify"
```

This will:

- Remove Store version (if still present)
- Patch your current Spotify installation
- Enable ad-free experience

---

## 🔄 Update Spotify Safely

If Spotify updates in the future, simply rerun the PowerShell script to re-apply the patch.

---

## 🧼 Uninstall BlockTheSpot (if needed)

To revert to the original Spotify:

1. Open PowerShell as Admin
2. Run:

```powershell
& "$env:APPDATA\Spotify\BlockTheSpot\uninstall.bat"
```

---

## ⚠️ Disclaimer

- This method is for educational purposes only.
- Use at your own risk. I am not responsible for any misuse or issues caused by third-party scripts.
- Respect Spotify's [terms of service](https://www.spotify.com/legal/end-user-agreement/).

---

## 📌 Credits

- BlockTheSpot GitHub: [https://github.com/mrpond/BlockTheSpot](https://github.com/mrpond/BlockTheSpot)
