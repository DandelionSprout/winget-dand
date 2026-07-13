## Packages uncreatable for various reasons (Unsorted):
* "Overføringsverktøy for brukere (veiviser for overføring av innstillinger)" (Missing OCMANAGE.dll)
* `https://catalog.update.microsoft.com/Search.aspx?q=kb5007651` (Fails to install)
* `https://github.com/shorthorn-project/One-Core-API-Binaries/releases` (Very unusual type of self-extracting file)
* `https://winget•tplant•com•au/cache/source•msix` / WingetPkgsSource / winget-font (All but `winget-font` are updated upstream too often. Installing the source MSIX, does not actually add it as a source repo. And the pkgs pipelines can't handle it either; see `https://github.com/microsoft/winget-pkgs/issues/400253`)
* AdtServer.msi (Requires Windows Server)
* AMD Chipset Drivers (Almost certainly "InternetOpenUrl() failed.")
* AMD Cleanup Utility ("InternetOpenUrl() failed.")
* AMD Ryzen Master (Very weird installer)
* AMD Software: Adrenalin Edition ("Download Not Complete" anti-"external access" measures)
* Bluegrams.ScreenRuler (Supposedly broke repo guidelines about SourceForge)
* Cisco Packet Tracer (Installer is behind a login wall)
* COAA.PlanePlotter (Pipeline bug treats the launch prompt as that it hasn't finished installing)
* Collabora Office (Version number in registry collides with LibreOffice)
* Command & Conquer: Red Alert 2 & Yuri's Revenge (Has the paid version of Red Alert 2 in a hardcoded folderpath as a dependency for silent installs)
* crypto20111.IDR (Has disasm as a post-installation dependency; hard to tell which disasm version is the correct one)
* DuckStation's .exe installers (Heavily customised installer)
* EitherMouse ("System.Xml.XmlException: 'v3' is an undeclared prefix."; `https://stackoverflow•com/questions/7557464/workaround-for-undeclared-prefix-error-on-xelement-load`)
* Elixir-lang.Elixir (The only post-install .exe is the uninstaller)
* EpicGames.EpicOnlineServicesSDK.C (Constantly error -2147467260)
* Epson Fax Utility (Requires separate scanner drivers)
* FMCM (Requires post-installation folder movement)
* FS-UAE (Requires manual folder moves)
* GarudaLinux.FireDragon (False positive "Can't install silently" pipeline error)
* GNU.APL (Missing "cyggcc_s-1.dll")
* Intel Fortran Compiler (Unresponsive veto-rights responsible)
* irzyxa.Volume2 (Can't be consistently silently installed: On some PCs throws "DAMAGE: after Normal block (#56) at 0x02CE1860")
* jklewa.ATVDesktopRemote (Requires Python 3)
* KB9114440 Network Diagnosis ("Not enough memory resources available (...)")
* Lenovo Dolby Vision Provisioning Kit (Unable to confirm if the package works or not.)
* LogExperts.LogExpert (Fails to detect .NET Runtime 10 x64 installations)
* Lynx Browser ("No SSL library found" seemingly no matter what)
* MediaWiki (Its only .exe-s in the zip archive are outdated Lua installers)
* Microsoft Audit Collection Services for UNIX/Linux (Has Microsoft System Center Operations Manager as a dependency)
* Microsoft Axe.Windows (Depends on ".NET Core Runtime 6.0 or newer", which could mean a lot of different things, at least 2 of which didn't work.)
* Microsoft Log Monitor / LogMonitor / Windows Container Tools (Requires a config JSON that is not automatically created)
* Microsoft Monitoring Agent / MOMAgent (Error 1603)
* Microsoft SQL Server 2025 Evaluation Edition (Refuses to recognise /ENU when Windows 11 is set to nb-NO)
* Microsoft System Center 2025 Operations Manager Server / SetupChainerUI.exe / SCOM 2025 (Requires manually setting the name of the "/SqlServerInstance")
* Microsoft System Center Data Protection Manager (Requires Windows Server)
* Microsoft System Center Operations Manager Gateway Server / MOMGateway.msi (Requires Windows Server)
* Microsoft System Center Operations Manager Reporting Server / OMReporting.msi (Requires Windows Server)
* Microsoft System Center Operations Manager Server / OMServer.msi (Requires Windows Server)
* Microsoft System Center Operations Manager Web Console (Error 1943)
* Microsoft System Center Orchestrator Runbook Designer (Pipelines get stuck)
* Microsoft System Center Orchestrator Service Management Automation Web Servers (Requires turning on the IIS service "Basic Authentication")
* Microsoft System Center Service Management Automation Runbook Worker (Requires manually setting SERVICEACCOUNT and SERVICEPASSWORD)
* Microsoft System Center Virtual Machine Manager Client (Winget-pkgs can't silently install it)
* Microsoft Visual C++ 2012/2013 Redistributable Arm32 (Incompatibility of the ARM64 pipelines)
* Microsoft Visual C++ 20xx Redistributable Itanium (Pipelines don't support it even if marked as Neutral)
* Microsoft.AccessibilityInsights (Its dev was pissy about it as of 2023)
* Microsoft.bpf_performance (Has "eBPF for Windows (MSI)" as a post-installation dependency)
* Microsoft.DotNet.docfx (Post-installation error "Cannot find config file C:\(...)\docfx.json")
* Microsoft.DotNet.Native.Framework.1.3 (No known Microsoft-owned distribution places for 1.3.24211.0)
* Microsoft.DotNet.Native.Runtime.1.7 (No known Microsoft-owned distribution places for 1.7.27422; `https://www.nuget.org/packages/Microsoft.Net.Native.Compiler/1.7.6` only has 1.7.25531)
* Microsoft.DotNet.Runtime.1_1 (Version number in registry collides with Microsoft.DotNet.Runtime.3_1)
* Microsoft.EnterpriseManagement.GatewayApprovalTool («Could not load file or assembly 'Microsoft.EnterpriseManagement.DataAccessLayer, (...)»)
* Microsoft.HIS.2020.MigrationTool / Host Integration Server (Overly complicated to use)
* Microsoft.MIDI.LoopbackService (Pipelines bafflingly complain about error 2180251649)
* Microsoft.ReportViewer 2015 (Has "Microsoft System CLR Types for SQL Server 2014" as a dependency)
* Microsoft.vcpkg (Post-installation requires a separate vcpkg-root app)
* Mozilla Thunderbird Nightly ("Device wide install for msix type is not supported in packaged context.")
* MozillaBuild (Not all that useful, since end-users must still build the post-installation files on their own)
* MPSeal («Could not load file or assembly 'Microsoft.EnterpriseManagement.Core, (...)»)
* Netbird (ESET detection)
* NTCore DisasMSIL (Its only .exe is a non-interactive test)
* NVIDIA Control Panel (AppX inside self-extracting 7Z, no currently known installer switches dedicated to it.)
* PatrickGaskin.PulseAudio / pgaskin (Setup installer doesn't work; while the portable `pulseaudio•exe` fails with `../../src/pulseaudio/src/pulsecore/core-util.c: Secure directory creation not supported on this platform.`)
* PDFMachine (.exe is in a .zip inside a .zip)
* PHP "Test Pack" ("The package file is not a valid zip archive.")
* PHP.PHP "tests package (phpt)" ("The package file is not a valid zip archive.")
* pl4nty.winget-pkgs-selfhost (Its GitHub repo's owner stated it wasn't his app.)
* PostGIS for PostgreSQL (Requires post-installation folder moves)
* PSAppDeployToolkit ("This application is designed to be used with the PSAppDeployToolkit PowerShell module and should not be directly invoked.")
* puhitaku.mtplvcap (Requires a Nikon DSLR device to run properly)
* PyEnv (Error 240)
* Python's appendpath.msi (Installer crashes silently with 0xc00000FD)
* Python's core.msi ("The TARGETDIR variable must be provided when invoking this installer.")
* Python's core_d.msi ("The TARGETDIR variable must be provided when invoking this installer.")
* Python's core_pdb.msi ("The TARGETDIR variable must be provided when invoking this installer.")
* Python's dev.msi (Installer crashes silently with 0xc00000FD)
* Python's dev_d.msi ("The TARGETDIR variable must be provided when invoking this installer.")
* Python's doc.msi (Installer crashes silently with 0xc00000FD)
* Python's exe.msi ("The TARGETDIR variable must be provided when invoking this installer.")
* Python's exe_d.msi ("The TARGETDIR variable must be provided when invoking this installer.")
* Python's exe_pdb.msi ("The TARGETDIR variable must be provided when invoking this installer.")
* Python's freethreaded.msi ("The TARGETDIR variable must be provided when invoking this installer.")
* Python's freethreaded_d.msi ("The TARGETDIR variable must be provided when invoking this installer.")
* Python's freethreaded_pdb.msi ("The TARGETDIR variable must be provided when invoking this installer.")
* Python's lib.msi (Installer crashes silently with 0xc00000FD)
* Python's lib_d.msi ("The TARGETDIR variable must be provided when invoking this installer.")
* Python's lib_pdb.msi ("The TARGETDIR variable must be provided when invoking this installer.")
* Python's path.msi (Installer crashes silently with 0xc00000FD)
* Python's pip.msi (Is merely a bootstrap, and not the actual pip package)
* Python's tcltk.msi (Installer crashes silently with 0xc00000FD)
* Python's test.msi (Installer crashes silently with 0xc00000FD)
* Python's ucrt.msi (Installer crashes silently with 0xc00000FD)
* RadioDJ (Requires a very, very insecurely configured MySQL in order for a silent installation to succeed)
* RetriX ("An error occured during the app package analysis")
* Samsung.Escargot (Depends on the WebAssembly library "Walrus", for which no executables exist)
* Samsung.Odin (No widely established installer URLs)
* Sniffnet (Has Npcap as a dependency)
* Update Root Certificates ("The package file is not a valid zip archive.")
* USBip-win(2) (Apparently requires driver test-signing system mode?)
* WinDump (Has Npcap as dependency)
* Wine Gecko ("The file browser!blocklist.xml can't be installed because the file doesn't exist in the cabinet file winegecko.cab. (...)")
* Wine Mono (Bafflingly tries to start a 2nd installer for a support tool before having finished the 1st installer)
* Xensam Xearch (No known download link)
* RabbitMQ (Installation fails with error 21)
* Microsoft WindowsWorkload pretty much anything (No known download links)

## Can't be silently installed:
* `https://www•mousemux•com/files/mousemux-v2-installer.exe`
* Anything that uses InstallForge (No silent switches)
* Audeze.AudezeHQ
* AVerMedia anything
* Banking4 Home
* BenQ anything (Gets stuck on pointless VCredist installation prompt)
* BrunnerInnovation.vJoy
* cardPresso
* Clue digital ordbok (Can't be silently installed, especially as its MSI version is fake)
* CM&V.DVBViewerDemo
* CyberLink pretty much anything
* * Ultra HD Blu-ray Advisor (`/S /v/qn` fails to make InstallShield progress silently for this app; a strange "Customer Information" prompt is possibly a factor)
* Devail1.WindowCenterResize
* Eclipso Toolbox (+ Time-expirant installer URL)
* Epson Firmware Updater
* Epson Product Setup
* EqualizerAPO(64) (Gets stuck on "Please select the devices for which Equalizer APO is to be installed.")
* ESET Online Scanner
* Final Fantasy XIV
* Fluent Store
* FreeFileSync
* Fujitsu ScanSnap Home
* GamesCleaner setup
* Genshin Impact / MiHoYo / HoYoPlay / Cognosphere
* Google WebP codec
* GPL / Artifex Software Ghostscript (The portable ZIPs may or may not work better)
* HP Support Assistant
* HP Universal Printer Driver / Universal Printing
* InstallForge
* Intel Memory and Storage Tool CLI
* K7 Antivirus Premium (Custom installer)
* Microsoft Remote Desktop Connection (No known silent switches)
* Microsoft.WindowsHardwareLabKit
* Mideej
* NAVER.Whale
* Nevrona Rave (Gets stuck on "You must enter your serial number.")
* Npcap
* Nvidia 3DVision USB Driver
* On-premises data gateway Microsoft
* PowerPanel Business Local/Remote (Gets stuck on "Please select one component to install.")
* Qt Linguist
* Samsung Browser for Windows
* TeX Live
* TizenProject.Studio
* TP-Link.tpPLC
* TuneBlade
* VirtİO's MSI versions
* Winpcap
* wxTED (Gets stuck on a prompt on whether to restart Explorer•exe or not)
* Xbox main EXE
* Yamaha.AG08Controller
* Yamaha.ConsoleFileConverter
* Yamaha.DM3Editor
* Yamaha.MOXFRemoteEditor
* 'Vense Connect (Driver install prompt that can only be closed manually)
* 'Vense Remote (Driver install prompt that can only be closed manually)
* Saleae.Logic2 (Driver install prompt that can only be closed manually)
* Thrustmaster.TARGET (Driver install prompt that can only be closed manually)
* VueScan (Driver install prompt that can only be closed manually)
* AlkaidLab.foundation-sunshine (Known to require a driver install)
* Jigsaw.Outline (Driver install prompt that can only be closed manually)
* IsaoMaruoka.Pixia (Silent installation fails with error 4294967292)
* Microsoft Office Subject Interface Packages for Digitally Signing VBA Projects / Sips (Gets stuck on the final prompt, "Files extracted successfully.")
* Klarna Desktop App (Considers its login screen to be part of the installation process)
* Locale Emulator
* Motorola Software Fix (Driver install prompt that can only be closed manually)

## App is pointless:
* VLC FreeSans font (Pointless due to it being a singular GNU-available font)
* gnome.phodav (Almost certainly an outdated version of Spice.SpiceWebDAVd)
* GNU.gzip (Probably made irrelevant and extremely outdated by GnuWin32.Gzip)
* Microsoft Defender Antivirus security intelligence updates (It's only relevant for offline computers, but offline computers can't use Winget.)
* Microsoft.ShaderConductor (Pointless due to containing an outdated version of Microsoft.DirectX.ShaderCompiler)
* Microsoft.SimpleRemote (Pretty much just one big vulnerability + Depends on another and unknown app)
* Mozilla.Firefox.EMEfree (The app is completely pointless)

## App doesn't work or is incomprehensible:
* `https://github.com/dekotan24/iwara-downloader`
* Abdi-Suufi.WeatherApp
* Apertus Forecast
* BrianPeek.MultipleWiimoteTester/WiimoteLib
* EdenwareApps.Megacubo
* EuanRiggins.BulkURLOpener
* GamesCleaner portable ("Zugriffsverletzung bei Adresse 004CFF50 in Modul 'GamesCleaner.exe'. Lesen von Adresse 00000000")
* GNOME Glom (Crashes on launch)
* Hydraulic.Conveyor
* JFrog.ArtifactoryCommunityEdition
* lixkote PRIExplorer ("This application could not be started")
* Microsoft GDI+ Detection Tool
* Microsoft Office 365 Centralized Deployment Checker
* Microsoft ROS / Robot Operating System (Completely incomprehensible how it works)
* Microsoft SQLToolsService Migration
* Microsoft Update Health Tools
* Microsoft.Azure.WindowsVMAgent
* Microsoft.Delprof
* Microsoft.legacyapp
* Microsoft.PhyloD (App's purpose and commands are incomprehensible)
* Microsoft.settingchange
* Microsoft.SystemCenterManagement(...)
* Microsoft.Teams.NetworkAssessmentTool
* Microsoft.WindowsAppRuntime.2.Experimental
* Mupen64Plus-Core (Incomprehensible setup process)
* NETGEAR.RAIDar (Fails to detect Java system installations)
* osmanonurkoc.WinGetInstaller
* Samsung CHashApp / ScanAndDecode
* samuelngs.apple-emoji-ttf
* WeatherWise
* winget-new-repos DanielTaufiq
* UniGetUI Widgets (Compatibility removed in newer UniGetUI versions; see `https://github.com/Devolutions/UniGetUI/issues/4798`)

## All sorts of certificate errors:
* 2fast (ZIP)
* ActualBudget AppX
* AdventurerClientJS AppX
* AnyFSE AppX
* Baulk AppX
* Bifrost/SamloaderKotlin MSIX
* BookViewer3 / BookViewerApp3 (ZIP)
* chARpack AppX
* Cynnexis Tide MSIX
* FluentFlyouts (MSIXBundle)
* Flycast AppX
* gabboxl.FluentWeather (MSIXBundle)
* Gorilla UI
* HDRImageViewer (ZIP)
* Hiddify MSIX
* Houseclub FrayxRulez (MSIXBundle)
* Intag MSIX
* IRCameraView (ZIP)
* KeePassPasskey (ZIP)
* Kodi MSIX
* LRReader (MSIXBundle)
* Microsoft eBPF for Windows - MSI (Doesn't have a valid signature... in an MSI file)
* Microsoft.SensorExplorer / busiotools (MSIXBundle)
* Mockoon AppX
* Mélodie Feugy AppX
* Ossia Score AppXBundle
* Passbolt (ZIP)
* RetroArch AppX
* RevoltChat AppX
* SimpleWeather (MSIXBundle)
* TasksORG MSIX
* TheElixZammuto Moonlight UWP (MSIXBundle)
* TouchXRPT (ZIP)
* Tracky-Mouse MSIX
* UltraPad/RectifyPad MSIX
* underpig1 Octos MSIX
* Unpaint
* VideoLAN.VLC-UWP (Also lacks "SharedLibrary.dll", etc.)
* WebcamOnDesktop (MSIXBundle)
* Wino Mail (MSIXBundle)
* XBSX2 (MSIXBundle)

## Time-expirant installer URLs:
* 3DMark
* ASUS anything on rog•asus•com
* Azure VPN Client (Version on appcenterMS has time-expirant installer URLs)
* BlackBerry Access
* Citrix DeviceTrust Client Extension
* Cricut Design Space
* Game Jolt anything
* ItchIO anything except its main client
* Nvidia.Nsight.Systems
* Panda3DS' nightly builds
* Realtek anything
* Splice Instrument

## HTTP "Forbidden" or similar:
* AmpliTube
* ASUS anything hosted on asuswebstorageCOM (HTTP "Unauthorised")
* BatchPatch (Installer download is somehow generated client-side from a "tmstv" script thingie)
* ExecTI Winaero
* IK Product Manager
* Mod The Sims anything
* Native Access
* No$gba
* phpBB•com
* Segger J-Link (Anti-bot measures for its download link)

## Self-extracting 7Z-s disguised as .exe-s:
* Microsoft Endpoint Community Manager (Self-extracting 7Z)
* Microsoft Keyboard Layout Creator (Setup .exe-/.msi-s inside self-extracting 7Z)
* ZohoCRM (Self-extracting 7Z)

## "No supported installer(s) found in zip archive.":
* Apache Maven
* DirectoryLister
* dxwrapper (elishacloud)
* FineFTP Server
* GNOME atk
* GNOME gail
* GNOME gnome-common
* GNOME gnome-vfs
* GNOME goocanvas
* GNOME gtkhtml
* GNOME gtksourceview
* GNOME intltool
* GNOME libcroco
* GNOME libglade
* GoldSrcModelThumbnailProvider
* Google.re2
* Gradle Distributions
* KeeperSecurity keeper-sdk-dotnet / PowerCommander
* kemnnx64
* Kotlin Language Server
* LazyDuchess.MonoPatcher
* LazyDuchess.TS2-Extender
* libsdl-org.SDL
* Microsoft QDK Samples
* Microsoft React Native WinRT
* Microsoft UEFI Debug Tools
* Microsoft.FactoryOrchestrator Service
* Microsoft.vc-ue-extensions
* Microsoft.Windows-appsample-marble-maze
* Microsoft.Windows-appsample-photo-editor
* Microsoft winget-cli-restsource
* Mozilla CrashReporter Symbols
* Npcap SDK
* NVDA Controller Client
* NVIDIA.CCCL
* OpenBIOS.OpenBIOS
* pascatl.ha-dhl
* PHP.PHP "Development package (SDK to develop PHP extensions)"
* PHP.PHP Debug Pack
* Pixel Streaming Infrastructure
* SignPath.CryptoProviders.Cryptoki
* simdjson singleheader
* Tiny UI Fix for The Sims 3
* Ultimate ASI Loader
* WebView2Browser
* windows-heic-thumbnails
* zlib
* Microsoft.OnnxRuntime

## Ruled out from "Project Portable MSIX-s" due to internal EXE-s not launching:
* DavidSungaila.SUBSTitute
* Elgato.WaveLink (Fails to assign the "wavelink" protocol)
* Iterate.MountainDuck
* Microsoft.AppControlPolicyWizard
* Microsoft.WindowsApp
* PowerClouds.CertoNiuchacz
* Prog.ProgTV.3
* Schlaubi.Tonbrett ("Failed to launch JVM")
* SEA.OssAccess
* Sparxsoft.DatabasePilot

## False positive detections:
* Bioruebe.UniExtract2 (False positive malware detection by Sophos)
* Bol-van's builds of Zapret2 (Avira/Avast false positives; https://github.com/microsoft/winget-pkgs/pull/375864#issuecomment-4477591311)
* Dinger.RDHost (ESET false positive)
* Moeary.IwaraTool (False positive malware detections by at least 2 companies)
* WebTorrent Desktop (False positive malware detection by Microsoft Defender)
* łzbench (A likely false positive detection by ESET)

## I cannot in good spirit add these due to my personal conscience, but I wouldn't stop others from adding them:
* Microsoft.Services.Store.Engagement (I'm in the adblocking community for a reason)
* Microsoft.Advertising.Xaml (Same reason)
* VLC Skin Editor (Requires Java)
* Apache Tomcat (Requires Java)
* Apache Lenya (Requires Java)
* PSO2 SymbolArt ThumbnailHandler (Weebery)
* ZipmodThumbnailHandler (Weebery)
* ExplorerLens (Vibecoding with various documentation falsehoods)
* AirDash (I have genuine deep phobia of the word Flutter and anything related to it)
* Namida (I have genuine deep phobia of the word Flutter and anything related to it)
* SoftOrbits Icon Maker (Raving imbeciles who only when trying to export an image shows a prompt about needing a licence)
* OneSky Forecast (Only handles USA and Canada)
* GNU Unifont (One of the top 5 ugliest fonts I've ever seen)
* Segoe UI Variable (The newest version is 2.03, but `https://learn.microsoft.com/en-us/windows/apps/design/downloads/` only offers 2.02)
