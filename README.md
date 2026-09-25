# Samply Bounce – Windows builds

FL Studio VST3 that captures your export and uploads it straight to [Samply](https://samply.app).
By [B Minor](https://bminorr.github.io).

## Install (Windows, no admin needed)
Open PowerShell and run:

```powershell
irm https://github.com/BMinorr/samply-bounce-releases/releases/latest/download/install-windows.ps1 | iex
```

Then in FL Studio: **Options → Manage plugins → Plugin search paths**, add
`%LOCALAPPDATA%\Programs\Common\VST3`, and click **Find installed plugins**.

After that the plugin keeps itself up to date: new versions are downloaded when FL Studio starts,
checked against the release signature, and become active the next time you open FL Studio.
