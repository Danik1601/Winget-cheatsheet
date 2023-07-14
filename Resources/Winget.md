# Repair

## Repair missing or corrupted system files documentation:

https://support.microsoft.com/topic/use-the-system-file-checker-tool-to-repair-missing-or-corrupted-system-files-79aa86cb-ca52-166a-92a3-966e85d4094e

## Deployment Image Servicing and Management:

`DISM.exe /Online /Cleanup-image /Restorehealth`

## System File Checker:

`sfc /scannow`

## Combined DISM and SFC:

`DISM.exe /Online /Cleanup-image /Restorehealth && sfc /scannow`

## Microsoft Support and Recovery Assistant:

https://support.microsoft.com/office/about-the-microsoft-support-and-recovery-assistant-e90bb691-c2a7-4697-a94f-88836856c72f

---

# Winget

## Documentation:

<https://learn.microsoft.com/windows/package-manager/>

## Microsoft Store:

<https://apps.microsoft.com/>

## Apps

### Microsoft Store Apps:

#### Essentials:

Microsoft App Installer:

```
winget install --id=9NBLGGH4NNS1 -e --accept-package-agreements &&
```

Microsoft Store:

```
winget install --id=9WZDNCRFJBMP -e --accept-package-agreements &&
```

Windows Terminal:

```
winget install --id=9N0DX20HK701 -e --accept-package-agreements &&
```

PowerShell:

```
winget install --id=9MZ1SNWT0N5D -e --accept-package-agreements &&
```

Snip & Sketch:

```
winget install --id=9MZ95KL8MR0L -e --accept-package-agreements &&
```

Windows Scan:

```
winget install --id=9WZDNCRFJ3PV -e --accept-package-agreements &&
```

Web Media Extensions:

```
winget install --id=9N5TDP8VCMHS -e --accept-package-agreements &&
```

HEIF Image Extensions:

```
winget install --id=9PMMSR1CGPWG -e --accept-package-agreements &&
```

Webp Image Extensions:

```
winget install --id=9PG2DK419DRG -e --accept-package-agreements &&
```

Raw Image Extension:

```
winget install --id=9NCTDW2W1BH8 -e --accept-package-agreements &&
```

AV1 Video Extension:

```
winget install --id=9MVZQVXJBQ9V -e --accept-package-agreements &&
```

VP9 Video Extensions:

```
winget install --id=9N4D0MSMP0PT -e --accept-package-agreements &&
```

MPEG-2 Video Extension:

```
winget install --id=9N95Q1ZZPMH4 -e --accept-package-agreements &&
```

HEVC Video Extensions

```
winget install --id=9NMZlZ57R3T7 -e --accept-package-agreements &&
```

Microsoft Remote Desktop:

```
winget install --id=9WZDNCRFJ3PS -e --accept-package-agreements &&
```

VLC UWP:

```
winget install --id=9NBLGGH4VVNH -e --accept-package-agreements &&
```

Telegram Desktop:

```
winget install --id=9NZTWSQNTD0S -e --accept-package-agreements &&
```

FB Messenger:

```
winget install --id=9WZDNCRF0083 -e --accept-package-agreements &&
```

WhatsApp Desktop:

```
winget install --id=9NKSQGP7F2NH -e --accept-package-agreements &&
```

VK Messenger:

```
winget install --id=9PMJG1606PSH -e --accept-package-agreements &&
```

Skype:

```
winget install --id=9WZDNCRFJ364 -e --accept-package-agreements &&
```

Speedtest by Ookla:

```
winget install --id=9NBLGGH4Z1JC -e --accept-package-agreements &&
```

TeamViewer: Remote Control:

```
winget install --id=9WZDNCRFJ0RH -e --accept-package-agreements &&
```

Windows Subsystem for Android:

```
winget install --id=9P3395VX91NR -e --accept-package-agreements &&
```

Windows Subsystem for Linux (Preview):

```
winget install --id=9P9TQF7MRM4R -e --accept-package-agreements &&
```

#### Gaming:

Xbox:

```
winget install --id=9MV0B5HZVK9Z -e --accept-package-agreements &&
```

Xbox Accessories:

```
winget install --id=9NBLGGH30XJ3 -e --accept-package-agreements &&
```

Xbox Game Bar:

```
winget install --id=9NZKPSTSNW4P -e --accept-package-agreements &&
```

Xbox Avatar Editor:

```
winget install --id=9NBLGGH4V0R3 -e --accept-package-agreements &&
```

#### Hardware specific:

AMD Radeon Software:

```
winget install --id=9NZ1BJQN6BHL -e --accept-package-agreements &&
```

AMD Link:

```
winget install --id=9PDZD398Q4FK -e --accept-package-agreements &&
```

Intel Graphics Command Center:

```
winget install --id=9PLFNLNT3G5G -e --accept-package-agreements &&
```

Intel Driver & Support Assistant:

```
winget install --id=Intel.IntelDriverAndSupportAssistant -e &&
```

NVIDIA Control Panel:

```
winget install --id=9NF8H0H7WMLT -e --accept-package-agreements &&
```

NVIDIA GeForce Experience:

```
winget install --id=Nvidia.GeForceExperience -e &&
```

My Dell:

```
winget install --id=9PN7T3JFPRZ6 -e --accept-package-agreements &&
```

HP Support Assistant:

```
winget install --id=9WZDNCRDRBFB -e --accept-package-agreements &&
```

MSI Center:

```
winget install --id=9NVMNJCR03XV -e --accept-package-agreements &&
```

Lenovo Vantage:

```
winget install --id=9WZDNCRFJ4MV -e --accept-package-agreements &&
```

MyASUS:

```
winget install --id=9N7R5S6B0ZZH -e --accept-package-agreements &&
```

HP Smart:

```
winget install --id=9WZDNCRFHWLH -e --accept-package-agreements &&
```

#### Other:

Microsoft Family Safety:

```
winget install --id=9PDJDJS743XF -e --accept-package-agreements &&
```

Windows File Recovery:

```
winget install --id=9N26S50LN705 -e --accept-package-agreements &&
```

iTunes:

```
winget install --id=9PB2MZ1ZMB1S -e --accept-package-agreements &&
```

ShareX:

```
winget install --id=9NBLGGH4Z1SP -e --accept-package-agreements &&
```

HotSpot Shield VPN:

```
winget install --id=9WZDNCRDFNG7 -e --accept-package-agreements &&
```

#### Games:

Minecraft Launcher:

```
winget install --id=9PGW18NPBZV5 -e --accept-package-agreements &&
```

Roblox:

```
winget install --id=9NBLGGGZM6WM -e --accept-package-agreements &&
```

Minecraft Education Edition:

```
winget install --id=9NBLGGH4R2R6 -e --accept-package-agreements &&
```

### Win32 Apps:

#### Essentials:

```
winget install --id=Google.Chrome -e &&
winget install --id=Google.ChromeRemoteDesktop -e &&
winget install --id=Google.NearbyShare -e &&
winget install --id=Google.Drive -e &&
winget install --id=Parsec.Parsec -e &&
winget install --id=Transmission.Transmission -e &&
winget install --id=OBSProject.OBSStudio -e &&
winget install --id=Balena.Etcher -e &&
winget install --id=TheDocumentFoundation.LibreOffice -e &&
winget install --id=TheDocumentFoundation.LibreOffice.HelpPack -e &&
winget install --id=Microsoft.PCManager -e &&
winget install --id=Microsoft.WindowsPCHealthCheck -e &&
winget install --id=Microsoft.PowerToys -e &&
winget install --id=AnyDeskSoftwareGmbH.AnyDesk -e &&
winget install --id=Discord.Discord -e &&
winget install --id=GOG.Galaxy -e &&
winget install --id=Valve.Steam -e &&
winget install --id=EpicGames.EpicGamesLauncher -e &&
winget install --id=ElectronicArts.EADesktop -e &&
winget install --id=Ubisoft.Connect -e &&
winget install --id=Telegram.TelegramDesktop -e &&
winget install --id=WhatsApp.WhatsApp -e &&
winget install --id=Viber.Viber -e &&
```

#### Tools:

```
winget install --id=Seagate.SeaTools -e &&
winget install --id=HandBrake.HandBrake -e &&
winget install --id=RARLab.WinRAR -e &&
winget install --id=7zip.7zip -e &&
winget install --id=TimKosse.FileZilla.Client -e &&
winget install --id=Syncthing.Syncthing -e &&
winget install --id=SyncTrayzor.SyncTrayzor -e &&
winget install --id=Nextcloud.NextcloudDesktop -e &&
winget install --id=ownCloud.ownCloudDesktop -e &&
winget install --id=Olivia.VIA -e &&
winget install --id=PuTTY.PuTTY -e &&
winget install --id=CPUID.CPU-Z -e &&
winget install --id=CPUID.HWMonitor -e &&
winget install --id=TechPowerUp.GPU-Z -e &&
```

#### 2FA:

```
winget install --id=Twilio.Authy -e &&
```

#### Office:

```
winget install --id=TheDocumentFoundation.LibreOffice -e &&
winget install --id=TheDocumentFoundation.LibreOffice.HelpPack -e &&
winget install --id=Microsoft.Office -e &&
```

#### VPN:

```
winget install --id=ProtonTechnologies.ProtonVPN -e &&
winget install --id=TorProject.TorBrowser -e &&
winget install --id=LogMeIn.Hamachi -e &&
```

#### Virtualization & Containers:

```
winget install --id=Oracle.VirtualBox -e &&
winget install --id=RedHat.Podman -e &&
winget install --id=RedHat.Podman-Desktop -e &&
winget install --id=Docker.DockerDesktop -e &&
```

#### Development:

```
winget install --id=Microsoft.VisualStudioCode -e &&
winget install --id=Microsoft.VisualStudio.2022.Community -e &&
winget install --id=Google.AndroidStudio -e &&
winget install --id=Git.Git -e &&
winget install --id=GoLang.Go -e &&
winget install --id=OpenJS.NodeJS -e &&
```

#### DisplayLink:

```
winget install --id=DisplayLink.GraphicsDriver -e
```

#### Hardware:

```
winget install --id=Logitech.GHUB -e &&
winget install --id=SteelSeries.GG -e &&
winget install --id=PlayStation.DualSenseFWUpdater -e &&
```

#### Redistributables & runtimes:

##### Visual C++ Redistributables:

```
winget install --id=Microsoft.VCRedist.2005.x86 -e &&
winget install --id=Microsoft.VCRedist.2005.x64 -e &&
winget install --id=Microsoft.VCRedist.2008.x86 -e &&
winget install --id=Microsoft.VCRedist.2008.x64 -e &&
winget install --id=Microsoft.VCRedist.2010.x86 -e &&
winget install --id=Microsoft.VCRedist.2010.x64 -e &&
winget install --id=Microsoft.VCRedist.2012.x86 -e &&
winget install --id=Microsoft.VCRedist.2012.x64 -e &&
winget install --id=Microsoft.VCRedist.2013.x86 -e &&
winget install --id=Microsoft.VCRedist.2013.x64 -e &&
winget install --id=Microsoft.VCRedist.2015+.x86 -e &&
winget install --id=Microsoft.VCRedist.2015+.x64 -e &&
```

##### .NET Runtimes:

```
winget install --id=Microsoft.DotNet.Runtime.3 -e &&
winget install --id=Microsoft.DotNet.Runtime.5 -e &&
winget install --id=Microsoft.DotNet.Runtime.6 -e &&
winget install --id=Microsoft.DotNet.Runtime.7 -e &&
```

##### .NET Framework:

```
winget install --id=Microsoft.dotNetFramework -e &&
```

#### Upgrades:

```
Windows 10 Upgrade Assistant:
winget install --id=Microsoft.UpdateAssistant -e &&
Windows 11 Upgrade Assistant:
winget install --id=Microsoft.WindowsInstallationAssistant -e &&
PC Health Check:
winget install --id=Microsoft.WindowsPCHealthCheck -e &&
```

---

## Bundles:

### To get latest tools before bulk install:

```
winget install --id=9NBLGGH4NNS1 -e --accept-package-agreements &&
winget install --id=9WZDNCRFJBMP -e --accept-package-agreements &&
winget install --id=9N0DX20HK701 -e --accept-package-agreements &&
winget install --id=9MZ1SNWT0N5D -e --accept-package-agreements &&
winget upgrade --all
```

### Bare minimum:

```
winget install --id=9MZ95KL8MR0L -e --accept-package-agreements &&
winget install --id=9WZDNCRFJ3PV -e --accept-package-agreements &&
winget install --id=9N5TDP8VCMHS -e --accept-package-agreements &&
winget install --id=9PMMSR1CGPWG -e --accept-package-agreements &&
winget install --id=9PG2DK419DRG -e --accept-package-agreements &&
winget install --id=9NCTDW2W1BH8 -e --accept-package-agreements &&
winget install --id=9MVZQVXJBQ9V -e --accept-package-agreements &&
winget install --id=9N4D0MSMP0PT -e --accept-package-agreements &&
winget install --id=9N95Q1ZZPMH4 -e --accept-package-agreements &&
winget install --id=9NMZlZ57R3T7 -e --accept-package-agreements &&
winget install --id=9WZDNCRFJ3PS -e --accept-package-agreements &&
winget install --id=9NBLGGH4VVNH -e --accept-package-agreements &&
winget install --id=9NZTWSQNTD0S -e --accept-package-agreements &&
winget install --id=Google.Chrome -e &&
winget install --id=Google.ChromeRemoteDesktop -e &&
winget install --id=Google.NearbyShare -e &&
winget install --id=Google.Drive -e &&
winget install --id=Parsec.Parsec -e &&
winget install --id=Transmission.Transmission -e &&
winget install --id=OBSProject.OBSStudio -e &&
winget install --id=Balena.Etcher -e &&
winget install --id=TheDocumentFoundation.LibreOffice -e &&
winget install --id=TheDocumentFoundation.LibreOffice.HelpPack -e &&
winget install --id=Microsoft.PCManager -e &&
winget install --id=Microsoft.WindowsPCHealthCheck -e &&
winget install --id=Microsoft.PowerToys -e &&
winget install --id=Microsoft.VisualStudioCode -e &&
winget install --id=Git.Git -e &&
winget upgrade --all
```

### Full package:

```
winget install --id=9NBLGGH4NNS1 -e --accept-package-agreements &&
winget install --id=9N0DX20HK701 -e --accept-package-agreements &&
winget install --id=9MZ1SNWT0N5D -e --accept-package-agreements &&
winget install --id=9MZ95KL8MR0L -e --accept-package-agreements &&
winget install --id=9WZDNCRFJ3PV -e --accept-package-agreements &&
winget install --id=9N5TDP8VCMHS -e --accept-package-agreements &&
winget install --id=9PMMSR1CGPWG -e --accept-package-agreements &&
winget install --id=9PG2DK419DRG -e --accept-package-agreements &&
winget install --id=9NCTDW2W1BH8 -e --accept-package-agreements &&
winget install --id=9MVZQVXJBQ9V -e --accept-package-agreements &&
winget install --id=9N4D0MSMP0PT -e --accept-package-agreements &&
winget install --id=9N95Q1ZZPMH4 -e --accept-package-agreements &&
winget install --id=9NMZlZ57R3T7 -e --accept-package-agreements &&
winget install --id=9NZKPSTSNW4P -e --accept-package-agreements &&
winget install --id=9WZDNCRFJ3PS -e --accept-package-agreements &&
winget install --id=9NZTWSQNTD0S -e --accept-package-agreements &&
winget install --id=9PMJG1606PSH -e --accept-package-agreements &&
winget install --id=9WZDNCRFJ364 -e --accept-package-agreements &&
winget install --id=9NBLGGH4Z1JC -e --accept-package-agreements &&
winget install --id=9NBLGGH4VVNH -e --accept-package-agreements &&
winget install --id=9MV0B5HZVK9Z -e --accept-package-agreements &&
winget install --id=9NBLGGH30XJ3 -e --accept-package-agreements &&
winget install --id=9PGW18NPBZV5 -e --accept-package-agreements &&
winget install --id=Google.Chrome -e &&
winget install --id=Google.ChromeRemoteDesktop -e &&
winget install --id=Google.NearbyShare -e &&
winget install --id=Google.Drive -e &&
winget install --id=AnyDeskSoftwareGmbH.AnyDesk -e &&
winget install --id=Parsec.Parsec -e &&
winget install --id=Transmission.Transmission -e &&
winget install --id=OBSProject.OBSStudio -e &&
winget install --id=Balena.Etcher -e &&
winget install --id=TheDocumentFoundation.LibreOffice -e &&
winget install --id=TheDocumentFoundation.LibreOffice.HelpPack -e &&
winget install --id=Microsoft.PCManager -e &&
winget install --id=Microsoft.WindowsPCHealthCheck -e &&
winget install --id=Microsoft.PowerToys -e &&
winget install --id=ProtonTechnologies.ProtonVPN -e &&
winget install --id=Microsoft.VisualStudioCode -e &&
winget install --id=Git.Git -e &&
winget install --id=Discord.Discord -e &&
winget install --id=GOG.Galaxy -e &&
winget install --id=Valve.Steam -e &&
winget install --id=EpicGames.EpicGamesLauncher -e &&
winget install --id=ElectronicArts.EADesktop -e &&
winget install --id=Ubisoft.Connect -e &&
winget upgrade --all
```

### Full package (AMD & Intel & MSI Center & Logitech G HUB & SteelSeries GG & DualSense Firmware Updater):

```
winget install --id=9NBLGGH4NNS1 -e --accept-package-agreements &&
winget install --id=9N0DX20HK701 -e --accept-package-agreements &&
winget install --id=9MZ1SNWT0N5D -e --accept-package-agreements &&
winget install --id=9MZ95KL8MR0L -e --accept-package-agreements &&
winget install --id=9WZDNCRFJ3PV -e --accept-package-agreements &&
winget install --id=9N5TDP8VCMHS -e --accept-package-agreements &&
winget install --id=9PMMSR1CGPWG -e --accept-package-agreements &&
winget install --id=9PG2DK419DRG -e --accept-package-agreements &&
winget install --id=9NCTDW2W1BH8 -e --accept-package-agreements &&
winget install --id=9MVZQVXJBQ9V -e --accept-package-agreements &&
winget install --id=9N4D0MSMP0PT -e --accept-package-agreements &&
winget install --id=9N95Q1ZZPMH4 -e --accept-package-agreements &&
winget install --id=9NMZlZ57R3T7 -e --accept-package-agreements &&
winget install --id=9NZKPSTSNW4P -e --accept-package-agreements &&
winget install --id=9WZDNCRFJ3PS -e --accept-package-agreements &&
winget install --id=9NZTWSQNTD0S -e --accept-package-agreements &&
winget install --id=9PMJG1606PSH -e --accept-package-agreements &&
winget install --id=9WZDNCRFJ364 -e --accept-package-agreements &&
winget install --id=9NBLGGH4Z1JC -e --accept-package-agreements &&
winget install --id=9NBLGGH4VVNH -e --accept-package-agreements &&
winget install --id=9MV0B5HZVK9Z -e --accept-package-agreements &&
winget install --id=9NBLGGH30XJ3 -e --accept-package-agreements &&
winget install --id=9PGW18NPBZV5 -e --accept-package-agreements &&
winget install --id=9NZ1BJQN6BHL -e --accept-package-agreements &&
winget install --id=9PDZD398Q4FK -e --accept-package-agreements &&
winget install --id=9PLFNLNT3G5G -e --accept-package-agreements &&
winget install --id=9NVMNJCR03XV -e --accept-package-agreements &&
winget install --id=Google.Chrome -e &&
winget install --id=Google.ChromeRemoteDesktop -e &&
winget install --id=Google.NearbyShare -e &&
winget install --id=Google.Drive -e &&
winget install --id=AnyDeskSoftwareGmbH.AnyDesk -e &&
winget install --id=Parsec.Parsec -e &&
winget install --id=Transmission.Transmission -e &&
winget install --id=OBSProject.OBSStudio -e &&
winget install --id=Balena.Etcher -e &&
winget install --id=TheDocumentFoundation.LibreOffice -e &&
winget install --id=TheDocumentFoundation.LibreOffice.HelpPack -e &&
winget install --id=Microsoft.PCManager -e &&
winget install --id=Microsoft.WindowsPCHealthCheck -e &&
winget install --id=Microsoft.PowerToys -e &&
winget install --id=ProtonTechnologies.ProtonVPN -e &&
winget install --id=Microsoft.VisualStudioCode -e &&
winget install --id=Git.Git -e &&
winget install --id=Discord.Discord -e &&
winget install --id=GOG.Galaxy -e &&
winget install --id=Valve.Steam -e &&
winget install --id=EpicGames.EpicGamesLauncher -e &&
winget install --id=ElectronicArts.EADesktop -e &&
winget install --id=Ubisoft.Connect -e &&
winget install --id=Intel.IntelDriverAndSupportAssistant -e &&
winget install --id=Logitech.GHUB -e &&
winget install --id=SteelSeries.GG -e &&
winget install --id=PlayStation.DualSenseFWUpdater -e &&
winget upgrade --all
```

### Working PCs:

```
winget install --id=9NBLGGH4NNS1 -e --accept-package-agreements &&
winget install --id=9WZDNCRFJBMP -e --accept-package-agreements &&
winget install --id=9N0DX20HK701 -e --accept-package-agreements &&
winget install --id=9MZ1SNWT0N5D -e --accept-package-agreements &&
winget install --id=9MZ95KL8MR0L -e --accept-package-agreements &&
winget install --id=9WZDNCRFJ3PV -e --accept-package-agreements &&
winget install --id=9N5TDP8VCMHS -e --accept-package-agreements &&
winget install --id=9PMMSR1CGPWG -e --accept-package-agreements &&
winget install --id=9PG2DK419DRG -e --accept-package-agreements &&
winget install --id=9NCTDW2W1BH8 -e --accept-package-agreements &&
winget install --id=9MVZQVXJBQ9V -e --accept-package-agreements &&
winget install --id=9N4D0MSMP0PT -e --accept-package-agreements &&
winget install --id=9N95Q1ZZPMH4 -e --accept-package-agreements &&
winget install --id=9NMZlZ57R3T7 -e --accept-package-agreements &&
winget install --id=9WZDNCRFJ3PS -e --accept-package-agreements &&
winget install --id=9NBLGGH4VVNH -e --accept-package-agreements &&
winget install --id=9NZTWSQNTD0S -e --accept-package-agreements &&
winget install --id=9NKSQGP7F2NH -e --accept-package-agreements &&
winget install --id=Google.Chrome -e &&
winget install --id=Google.ChromeRemoteDesktop -e &&
winget install --id=Google.NearbyShare -e &&
winget install --id=AnyDeskSoftwareGmbH.AnyDesk -e &&
winget install --id=Transmission.Transmission -e &&
winget install --id=TheDocumentFoundation.LibreOffice -e &&
winget install --id=TheDocumentFoundation.LibreOffice.HelpPack -e &&
winget install --id=Microsoft.VCRedist.2005.x86 -e &&
winget install --id=Microsoft.VCRedist.2005.x64 -e &&
winget install --id=Microsoft.VCRedist.2008.x86 -e &&
winget install --id=Microsoft.VCRedist.2008.x64 -e &&
winget install --id=Microsoft.VCRedist.2010.x86 -e &&
winget install --id=Microsoft.VCRedist.2010.x64 -e &&
winget install --id=Microsoft.VCRedist.2012.x86 -e &&
winget install --id=Microsoft.VCRedist.2012.x64 -e &&
winget install --id=Microsoft.VCRedist.2013.x86 -e &&
winget install --id=Microsoft.VCRedist.2013.x64 -e &&
winget install --id=Microsoft.VCRedist.2015+.x86 -e &&
winget install --id=Microsoft.VCRedist.2015+.x64 -e &&
winget install --id=Microsoft.DotNet.Runtime.3 -e &&
winget install --id=Microsoft.DotNet.Runtime.5 -e &&
winget install --id=Microsoft.DotNet.Runtime.6 -e &&
winget install --id=Microsoft.DotNet.Runtime.7 -e &&
winget install --id=Microsoft.dotNetFramework -e &&
winget upgrade --all
```

### Working PCs (Win32 versions of Telegram, WhatsApp, Viber):

```
winget install --id=9NBLGGH4NNS1 -e --accept-package-agreements &&
winget install --id=9WZDNCRFJBMP -e --accept-package-agreements &&
winget install --id=9N0DX20HK701 -e --accept-package-agreements &&
winget install --id=9MZ1SNWT0N5D -e --accept-package-agreements &&
winget install --id=9MZ95KL8MR0L -e --accept-package-agreements &&
winget install --id=9WZDNCRFJ3PV -e --accept-package-agreements &&
winget install --id=9N5TDP8VCMHS -e --accept-package-agreements &&
winget install --id=9PMMSR1CGPWG -e --accept-package-agreements &&
winget install --id=9PG2DK419DRG -e --accept-package-agreements &&
winget install --id=9NCTDW2W1BH8 -e --accept-package-agreements &&
winget install --id=9MVZQVXJBQ9V -e --accept-package-agreements &&
winget install --id=9N4D0MSMP0PT -e --accept-package-agreements &&
winget install --id=9N95Q1ZZPMH4 -e --accept-package-agreements &&
winget install --id=9NMZlZ57R3T7 -e --accept-package-agreements &&
winget install --id=9WZDNCRFJ3PS -e --accept-package-agreements &&
winget install --id=9NBLGGH4VVNH -e --accept-package-agreements &&
winget install --id=Google.Chrome -e &&
winget install --id=Google.ChromeRemoteDesktop -e &&
winget install --id=Google.NearbyShare -e &&
winget install --id=AnyDeskSoftwareGmbH.AnyDesk -e &&
winget install --id=Telegram.TelegramDesktop -e &&
winget install --id=WhatsApp.WhatsApp -e &&
winget install --id=Viber.Viber -e &&
winget install --id=Transmission.Transmission -e &&
winget install --id=TheDocumentFoundation.LibreOffice -e &&
winget install --id=TheDocumentFoundation.LibreOffice.HelpPack -e &&
winget install --id=Microsoft.VCRedist.2005.x86 -e &&
winget install --id=Microsoft.VCRedist.2005.x64 -e &&
winget install --id=Microsoft.VCRedist.2008.x86 -e &&
winget install --id=Microsoft.VCRedist.2008.x64 -e &&
winget install --id=Microsoft.VCRedist.2010.x86 -e &&
winget install --id=Microsoft.VCRedist.2010.x64 -e &&
winget install --id=Microsoft.VCRedist.2012.x86 -e &&
winget install --id=Microsoft.VCRedist.2012.x64 -e &&
winget install --id=Microsoft.VCRedist.2013.x86 -e &&
winget install --id=Microsoft.VCRedist.2013.x64 -e &&
winget install --id=Microsoft.VCRedist.2015+.x86 -e &&
winget install --id=Microsoft.VCRedist.2015+.x64 -e &&
winget install --id=Microsoft.DotNet.Runtime.3 -e &&
winget install --id=Microsoft.DotNet.Runtime.5 -e &&
winget install --id=Microsoft.DotNet.Runtime.6 -e &&
winget install --id=Microsoft.DotNet.Runtime.7 -e &&
winget install --id=Microsoft.dotNetFramework -e &&
winget upgrade --all
```
