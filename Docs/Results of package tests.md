## Packages uncreateable for various reasons (Unsorted):
* "Overføringsverktøy for brukere (veiviser for overføring av innstillinger)" (Missing OCMANAGE.dll)
* 'Vense Connect (Driver install prompt that can only be closed manually)
* 'Vense Remote (Driver install prompt that can only be closed manually)
* `https://catalog.update.microsoft.com/Search.aspx?q=kb5007651` (Fails to install)
* `https://github.com/shorthorn-project/One-Core-API-Binaries/releases` (Very unusual type of self-extracting file)
* `https://winget•tplant•com•au/cache/source•msix` (Installing the source MSIX, does not actually add it as a source repo.)
* `https://www•mousemux•com/files/mousemux-v2-installer.exe` (Can't be silently installed)
* AdtServer.msi (Requires Windows Server)
* AlkaidLab.foundation-sunshine (Known to require a driver install)
* AMD Chipset Drivers (Almost certainly "InternetOpenUrl() failed.")
* AMD Cleanup Utility ("InternetOpenUrl() failed.")
* AMD Ryzen Master (Very weird installer)
* AMD Software: Adrenalin Edition ("Download Not Complete" anti-"external access" measures)
* Audeze.AudezeHQ (Can't be silently installed)
* AVerMedia anything (Can't be silently installed)
* Banking4 Home (Can't be silently installed)
* BenQ anything (Can't be silently installed; gets stuck on pointless VCredist installation prompt)
* Bluegrams.ScreenRuler (Supposedly broke repo guidelines about SourceForge)
* BrunnerInnovation.vJoy (Can't be silently installed)
* cardPresso (Can't be silently installed)
* Cisco Packet Tracer (Installer is behind a login wall)
* Clue digital ordbok (Can't be silently installed, especially as its MSI version is fake)
* CM&V.DVBViewerDemo (Can't be silently installed)
* COAA.PlanePlotter (Pipeline bug treats the launch prompt as that it hasn't finished installing)
* Collabora Office (Version number in registry collides with LibreOffice)
* Command & Conquer: Red Alert 2 & Yuri's Revenge (Has the paid version of Red Alert 2 in a hardcoded folderpath as a dependency for silent installs)
* crypto20111.IDR (Has disasm as a post-installation dependency; hard to tell which disasm version is the correct one)
* Devail1.WindowCenterResize (Can't be silently installed)
* DuckStation's .exe installers (Heavily customised installer)
* Eclipso Toolbox (Can't be silently installed + Time-expirant installer URL)
* EitherMouse ("System.Xml.XmlException: 'v3' is an undeclared prefix."; `https://stackoverflow•com/questions/7557464/workaround-for-undeclared-prefix-error-on-xelement-load`)
* Elixir-lang.Elixir (The only post-install .exe is the uninstaller)
* EpicGames.EpicOnlineServicesSDK.C (Constantly error -2147467260)
* Epson Fax Utility (Requires separate scanner drivers)
* Epson Firmware Updater (Can't be silently installed)
* Epson Product Setup (Can't be silently installed)
* EqualizerAPO(64) (Can't be silently installed; gets stuck on "Please select the devices for which Equalizer APO is to be installed.")
* ESET Online Scanner (Can't be silently installed)
* Final Fantasy XIV (Can't be silently installed)
* Fluent Store (Can't be silently installed)
* FMCM (Requires post-installation folder movement)
* FreeFileSync (Can't be silently installed)
* FS-UAE (Requires manual folder moves)
* Fujitsu ScanSnap Home (Can't be silently installed)
* GamesCleaner setup (Can't be silently installed)
* GarudaLinux.FireDragon (False positive "Can't install silently" pipeline error)
* Genshin Impact / MiHoYo / HoYoPlay / Cognosphere (Can't be silently installed)
* gnome.phodav (Almost certainly an outdated version of Spice.SpiceWebDAVd)
* GNU.APL (Missing "cyggcc_s-1.dll")
* GNU.gzip (Probably made irrelevant and extremely outdated by GnuWin32.Gzip)
* Google WebP codec (Can't be silently installed)
* GPL / Artifex Software Ghostscript (Can't be silently installed. The portable ZIPs may or may not work better)
* HP Support Assistant (Can't be silently installed)
* HP Universal Printer Driver / Universal Printing (Can't be silently installed)
* InstallForge (Can't be silently installed)
* Intel Memory and Storage Tool CLI (Can't be silently installed)
* irzyxa.Volume2 (Can't be consistently silently installed: On some PCs throws "DAMAGE: after Normal block (#56) at 0x02CE1860")
* IsaoMaruoka.Pixia (Silent installation fails with error 4294967292)
* Jigsaw.Outline (Driver install prompt that can only be closed manually)
* jklewa.ATVDesktopRemote (Requires Python 3)
* K7 Antivirus Premium (Can't be silently installed; custom installer)
* KB9114440 Network Diagnosis ("Not enough memory resources available (...)")
* LogExperts.LogExpert (Fails to detect .NET Runtime 10 x64 installations)
* MediaWiki (Its only .exe-s in the zip archive are outdated Lua installers)
* Microsoft Audit Collection Services for UNIX/Linux (Has Microsoft System Center Operations Manager as a dependency)
* Microsoft Log Monitor / LogMonitor / Windows Container Tools (Requires a config JSON that is not automatically created)
* Microsoft Monitoring Agent / MOMAgent (Error 1603)
* Microsoft Office Subject Interface Packages for Digitally Signing VBA Projects / Sips (Gets stuck on the final prompt, "Files extracted successfully.")
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
* Microsoft.AppInstaller.WingetPkgsSource (Version number changes far too frequently to have the faintest hope of passing validation)
* Microsoft.bpf_performance (Has "eBPF for Windows (MSI)" as a post-installation dependency)
* Microsoft.DotNet.docfx (Post-installation error "Cannot find config file C:\(...)\docfx.json")
* Microsoft.DotNet.Runtime.1_1 (Version number in registry collides with Microsoft.DotNet.Runtime.3_1)
* Microsoft.EnterpriseManagement.GatewayApprovalTool («Could not load file or assembly 'Microsoft.EnterpriseManagement.DataAccessLayer, (...)»)
* Microsoft.HIS.2020.MigrationTool / Host Integration Server (Overly complicated to use)
* Microsoft.MIDI.LoopbackService (Pipelines bafflingly complain about error 2180251649)
* Microsoft.ReportViewer 2015 (Has "Microsoft System CLR Types for SQL Server 2014" as a dependency)
* Microsoft.ShaderConductor (Pointless due to containing an outdated version of Microsoft.DirectX.ShaderCompiler)
* Microsoft.SimpleRemote (Pretty much just one big vulnerability + Depends on another and unknown app)
* Microsoft.vcpkg (Post-installation requires a separate vcpkg-root app)
* Microsoft.WindowsHardwareLabKit (Can't be silently installed)
* Mideej (Can't be silently installed)
* Mozilla Thunderbird Nightly ("Device wide install for msix type is not supported in packaged context.")
* Mozilla.Firefox.EMEfree (The app is completely pointless)
* MozillaBuild (Not all that useful, since end-users must still build the post-installation files on their own)
* MPSeal («Could not load file or assembly 'Microsoft.EnterpriseManagement.Core, (...)»)
* NAVER.Whale (Can't be silently installed)
* Netbird (ESET detection)
* Nevrona Rave (Can't be silently installed; gets stuck on "You must enter your serial number.")
* Npcap (Can't be silently installed)
* NTCore DisasMSIL (Its only .exe is a non-interactive test)
* Nvidia 3DVision USB Driver (Can't be silently installed)
* Nvidia.Nsight.Systems (Constantly error -2147467260)
* On-premises data gateway Microsoft (Can't be silently installed)
* PatrickGaskin.PulseAudio / pgaskin (Installer doesn't work. Portable binaries may or may not work better)
* PDFMachine (.exe is in a .zip inside a .zip)
* PHP "Test Pack" ("The package file is not a valid zip archive.")
* PHP.PHP "tests package (phpt)" ("The package file is not a valid zip archive.")
* pl4nty.winget-pkgs-selfhost (Its GitHub repo's owner stated it wasn't his app.)
* PostGIS for PostgreSQL (Requires post-installation folder moves)
* PowerPanel Business Local/Remote (Can't be silently installed; gets stuck on "Please select one component to install.")
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
* Python's tcltk.msi (Installer crashes silently with 0xc00000FD)
* Python's test.msi (Installer crashes silently with 0xc00000FD)
* Python's ucrt.msi (Installer crashes silently with 0xc00000FD)
* Qt Linguist (Can't be silently installed)
* RadioDJ (Requires a very, very insecurely configured MySQL in order for a silent installation to succeed)
* RetriX ("An error occured during the app package analysis")
* Saleae.Logic2 (Driver install prompt that can only be closed manually)
* Samsung Browser for Windows (Can't be silently installed)
* Samsung.Escargot (Depends on the WebAssembly library "Walrus", for which no executables exist)
* Samsung.Odin (No widely established installer URLs)
* Sniffnet (Has Npcap as a dependency)
* TeX Live (Can't be silently installed)
* Thrustmaster.TARGET (Driver install prompt that can only be closed manually)
* TizenProject.Studio (Can't be silently installed)
* TP-Link.tpPLC (Can't be silently installed)
* TuneBlade (Can't be silently installed)
* Update Root Certificates ("The package file is not a valid zip archive.")
* VLC FreeSans font (Pointless due to it being a singular GNU-available font)
* VueScan (Driver install prompt that can only be closed manually)
* WinDump (Has Npcap as dependency)
* Wine Gecko ("The file browser!blocklist.xml can't be installed because the file doesn't exist in the cabinet file winegecko.cab. (...)")
* Wine Mono (Bafflingly tries to start a 2nd installer for a support tool before having finished the 1st installer)
* Winpcap (Can't be silently installed)
* wxTED (Can't be silently installed; gets stuck on a prompt on whether to restart Explorer.exe or not)
* Xbox main EXE (Can't be silently installed)
* Xensam Xearch (No known download link)
* Yamaha.AG08Controller (Can't be silently installed)
* Yamaha.ConsoleFileConverter (Can't be silently installed)
* Yamaha.DM3Editor (Can't be silently installed)
* Yamaha.MOXFRemoteEditor (Can't be silently installed)
* Python's pip.msi (Is merely a bootstrap, and not the actual pip package)
* Microsoft Remote Desktop Connection (Can't be silently installed; no known silent switches.)
* NVIDIA Control Panel (AppX inside self-extracting 7Z, no currently known installer switches dedicated to it.)
* Lenovo Dolby Vision Provisioning Kit (Unable to confirm if the package works or not.)
* Anything that uses InstallForge (Can't be silently installed; no silent switches.)
* Microsoft.DotNet.Native.Framework.1.3 (No known Microsoft-owned distribution places for 1.3.24211.0)
* USBip-win(2) (Apparently requires driver test-signing system mode?)

## App doesn't work or is incomprehensible:
* BrianPeek.MultipleWiimoteTester/WiimoteLib
* EdenwareApps.Megacubo
* EuanRiggins.BulkURLOpener
* GNOME Glom (Crashes on launch)
* `https://github.com/dekotan24/iwara-downloader`
* Microsoft Office 365 Centralized Deployment Checker
* Microsoft ROS / Robot Operating System (Completely incomprehensible how it works)
* Microsoft SQLToolsService Migration
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
* JFrog.ArtifactoryCommunityEdition
* Microsoft GDI+ Detection Tool
* WeatherWise
* Apertus Forecast
* Abdi-Suufi.WeatherApp
* GamesCleaner portable ("Zugriffsverletzung bei Adresse 004CFF50 in Modul 'GamesCleaner.exe'. Lesen von Adresse 00000000")
* winget-new-repos DanielTaufiq
* Microsoft Update Health Tools
* Hydraulic.Conveyor
* samuelngs.apple-emoji-ttf
* lixkote PRIExplorer ("This application could not be started")

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
* Kodi MSIX

## Time-expirant installer URLs:
* 3DMark
* ASUS anything on rog•asus•com
* Azure VPN Client (Version on appcenterMS has time-expirant installer URLs)
* BlackBerry Access
* Cricut Design Space
* Game Jolt anything
* ItchIO anything except its main client
* Realtek anything
* Splice Instrument
* Citrix DeviceTrust Client Extension

## HTTP "Forbidden" or similar:
* AmpliTube
* ExecTI Winaero
* IK Product Manager
* Mod The Sims anything
* Native Access
* No$gba
* ASUS anything hosted on asuswebstorageCOM (HTTP "Unauthorised")
* Segger J-Link (Anti-bot measures for its download link)
* BatchPatch (Installer download is somehow generated client-side from a "tmstv" script thingie)
* phpBB•com

## Self-extracting 7Z-s disguised as .exe-s:
* Microsoft Endpoint Community Manager (Self-extracting 7Z)
* Microsoft Keyboard Layout Creator (Setup .exe-/.msi-s inside self-extracting 7Z)
* ZohoCRM (Self-extracting 7Z)

## "No supported installer(s) found in zip archive.":
* Apache Maven
* DirectoryLister
* dxwrapper (elishacloud)
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
* Gradle Distributions
* KeeperSecurity keeper-sdk-dotnet / PowerCommander
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
* Mozilla CrashReporter Symbols
* Npcap SDK
* NVIDIA.CCCL
* OpenBIOS.OpenBIOS
* PHP.PHP "Development package (SDK to develop PHP extensions)"
* PHP.PHP Debug Pack
* Tiny UI Fix for The Sims 3
* Ultimate ASI Loader
* zlib
* kemnnx64
* WebView2Browser
* SignPath.CryptoProviders.Cryptoki
* windows-heic-thumbnails
* GoldSrcModelThumbnailProvider
* NVDA Controller Client
* simdjson singleheader
* FineFTP Server
* pascatl.ha-dhl

## Ruled out from "Project Portable MSIX-s" due to internal EXE-s not launching:
* Elgato.WaveLink (Fails to assign the "wavelink" protocol)
* Iterate.MountainDuck
* Microsoft.AppControlPolicyWizard
* PowerClouds.CertoNiuchacz
* Prog.ProgTV.3
* Schlaubi.Tonbrett ("Failed to launch JVM")
* SEA.OssAccess
* Sparxsoft.DatabasePilot
* Microsoft.WindowsApp
* DavidSungaila.SUBSTitute

## False positive detections:
* Bioruebe.UniExtract2 (False positive malware detection by Sophos)
* WebTorrent Desktop (False positive malware detection by Microsoft Defender)
* Moeary.IwaraTool (False positive malware detections by at least 2 companies)
* łzbench (A likely false positive detection by ESET)
* Dinger.RDHost (ESET false positive)
* Bol-van's builds of Zapret2 (Avira/Avast false positives; https://github.com/microsoft/winget-pkgs/pull/375864#issuecomment-4477591311)

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
