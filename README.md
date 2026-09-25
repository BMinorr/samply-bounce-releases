# Samply Bounce – builds & installers

FL Studio VST3 that captures your export and uploads it straight to [Samply](https://samply.app).
By [B Minor](https://bminorr.github.io).

## Windows (PowerShell – asks for administrator rights once)
```powershell
irm https://github.com/BMinorr/samply-bounce-releases/releases/latest/download/install-windows.ps1 | iex
```
Installs into `C:\Program Files\Common Files\VST3` (the VST3 folder FL Studio and Ableton scan) and lets
Windows users update just that plugin folder, so later updates need no admin.
Then in FL Studio: **Options → Manage plugins → Find installed plugins**.

## macOS (Terminal)
```bash
curl -fsSL https://github.com/BMinorr/samply-bounce-releases/releases/latest/download/install-macos.sh | bash
```
Then in FL Studio: **Options → Manage plugins → Find installed plugins**.

After the first install the plugin keeps itself up to date: new versions are downloaded when FL Studio
starts, checked against the release signature, and become active the next time you open FL Studio.
