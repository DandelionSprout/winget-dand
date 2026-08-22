♪ = Made it to extras.<br>
♫ = Suited for extras submitting?

## Packages uncreatable for various reasons (Unsorted):
* "Overføringsverktøy for brukere (veiviser for overføring av innstillinger)" (Missing OCMANAGE.dll)
* `https://catalog.update.microsoft.com/Search.aspx?q=kb5007651` (Fails to install)
* `https://github.com/shorthorn-project/One-Core-API-Binaries/releases` (Very unusual type of self-extracting file)
* `https://winget•tplant•com•au/cache/source(2)•msix` / WingetPkgsSource / winget-font (All but `winget-font` are updated upstream too often. Installing the source MSIX, does not actually add it as a source repo. The pkgs pipelines can't handle it either; see `https://github.com/microsoft/winget-pkgs/issues/400253`. And `winget-font` is in essence dead; see `https://github.com/pl4nty/winget-extras/pull/746`)
* AdtServer.msi (Requires Windows Server)
* AMD Chipset Drivers (Almost certainly "InternetOpenUrl() failed.")
* AMD Cleanup Utility ("InternetOpenUrl() failed.")
* AMD Ryzen Master (Very weird installer)
* ASUS Armoury Crate SE Service (No known installer URLs; the "Armoury Crate SE Installer" just installs the regular Armoury Crate)
* ASUS Business Manager (Strange installer)
* ASUS Device Discovery (Error 2147753984)
* ASUS DriverHub (Requires an ASUS motherboard to complete installation)
* ASUS System Control Interface 3 ("This version of ASUS System Control Interface driver of your machine cannot support some function, click "OK" for more information."⁽ˢⁱᶜ⁾)
* CertsUpdater Saber Interactive (No known installer URLs)
* Cisco Packet Tracer (Installer is behind a login wall)
* COAA.PlanePlotter (Pipeline bug treats the launch prompt as that it hasn't finished installing)
* Collabora Office (Version number in registry collides with LibreOffice; probably warrants re-testing now that I know how ProductCode works like.)
* crypto20111.IDR (Has disasm as a post-installation dependency; hard to tell which disasm version is the correct one)
* DuckStation's .exe installers (Heavily customised installer)
* EitherMouse ("System.Xml.XmlException: 'v3' is an undeclared prefix."; `https://stackoverflow•com/questions/7557464/workaround-for-undeclared-prefix-error-on-xelement-load`)
* Elixir-lang.Elixir (The only post-install .exe is the uninstaller)
* Epson Fax Utility (Requires separate scanner drivers)
* FMCM (Requires post-installation folder movement)
* FS-UAE (Requires manual folder moves)
* GNU.APL (Missing "cyggcc_s-1.dll")
* Intel Fortran Compiler (Unresponsive veto-rights responsible)
* irzyxa.Volume2 (The 2025 x64 builds throw "DAMAGE: after Normal block (#56) at 0x02CE1860" errors; see https://github.com/irzyxa/Volume2/issues/383)
* IwaraTool (Comically large amounts of malware engine detections)
* KB9114440 Network Diagnosis ("Not enough memory resources available (...)")
* Lenovo Dolby Vision Provisioning Kit (Unable to confirm if the package works or not.)
* LogExperts.LogExpert (Fails to detect .NET Runtime 10 x64 installations)
* Lynx Browser ("No SSL library found" seemingly no matter what)
* MediaWiki (Its only .exe-s in the zip archive are outdated Lua installers)
* Microsoft Audit Collection Services for UNIX/Linux (Has Microsoft System Center Operations Manager as a dependency)
* Microsoft Axe.Windows (Depends on ".NET Core Runtime 6.0 or newer", which could mean a lot of different things, at least 2 of which didn't work.)
* Microsoft Configuration Manager / ConfigMgr (7Z file)
* Microsoft Copilot (No known installer URLs; the Edge Beta HoloLens 2 MSIX builds only contain the "Sparse" stub versions of it as far as x64/x86 goes.)
* Microsoft Log Monitor / LogMonitor / Windows Container Tools (Requires a config JSON that is not automatically created)
* Microsoft Monitoring Agent / MOMAgent (Error 1603)
* Microsoft SQL Server 2025 Evaluation Edition (Refuses to recognise /ENU when Windows 11 is set to nb-NO)
* Microsoft System Center 2025 Operations Manager Server / SetupChainerUI.exe / SCOM 2025 (Requires manually setting the name of the "/SqlServerInstance")
* Microsoft System Center Data Protection Manager (Requires Windows Server)
* Microsoft System Center Operations Manager Gateway Server / MOMGateway.msi (Requires Windows Server)
* Microsoft System Center Operations Manager Reporting Server / OMReporting.msi (Requires Windows Server)
* Microsoft System Center Operations Manager Server / OMServer.msi (Requires Windows Server)
* Microsoft System Center Operations Manager Web Console (Error 1943)
* Microsoft System Center Orchestrator Service Management Automation Web Servers (Requires turning on the IIS service "Basic Authentication")
* Microsoft System Center Service Management Automation Runbook Worker (Requires manually setting SERVICEACCOUNT and SERVICEPASSWORD)
* Microsoft Visual C++ 20xx Redistributable Itanium (Pipelines don't support it even if marked as Neutral)
* Microsoft WindowsWorkload pretty much anything (No known download links)
* Microsoft.bpf_performance (Has "eBPF for Windows (MSI)" as a post-installation dependency)
* Microsoft.DotNet.docfx (Post-installation error "Cannot find config file C:\(...)\docfx.json")
* Microsoft.DotNet.Native.Framework.1.3 (No known Microsoft-owned distribution places for 1.3.24211.0)
* Microsoft.DotNet.Native.Runtime.1.7 (No known Microsoft-owned distribution places for 1.7.27422; `https://www.nuget.org/packages/Microsoft.Net.Native.Compiler/1.7.6` only has 1.7.25531)
* Microsoft.DotNet.Runtime.1_1 (Version number in registry collides with Microsoft.DotNet.Runtime.3_1; probably warrants re-testing now that I know how ProductCode works like.)
* Microsoft.EnterpriseManagement.GatewayApprovalTool («Could not load file or assembly 'Microsoft.EnterpriseManagement.DataAccessLayer, (...)»)
* Microsoft.HIS.2020.MigrationTool / Host Integration Server (Overly complicated to use)
* Microsoft.MIDI.LoopbackService (Pipelines bafflingly complain about error 2180251649)
* Microsoft.ReportViewer 2015 (Has "Microsoft System CLR Types for SQL Server 2014" as a dependency)
* Microsoft.WindowsAppRuntime.2.msix (Does not show up as an installed app post-installation)
* Microsoft.WindowsAppRuntime.DDLM.2.msix (Has Microsoft.WindowsAppRuntime.2.msix as a hard dependency, which must be of the same version and which is unlikely to be noticed as being already installed.)
* Microsoft.WindowsAppRuntime.Main.2.msix (Has Microsoft.WindowsAppRuntime.2.msix as a hard dependency, which must be of the same version and which is unlikely to be noticed as being already installed.)
* Microsoft.WindowsAppRuntime.Singleton.2.msix (Has Microsoft.WindowsAppRuntime.2.msix as a hard dependency, which must be of the same version and which is unlikely to be noticed as being already installed.)
* Mozilla Maintenance Service (Its Mozilla developers got *really* pissy about it)
* Mozilla Thunderbird Nightly ("Device wide install for msix type is not supported in packaged context.")
* MPSeal («Could not load file or assembly 'Microsoft.EnterpriseManagement.Core, (...)»)
* Netbird (ESET detection)
* NinjaOne (No known installer URLs)
* Norton anything (No easily apparent installer URLs, and I can't be bothered to look deeper into URLs since it's Norton)
* NTCore DisasMSIL (Its only .exe is a non-interactive test)
* NVIDIA Control Panel (AppX inside self-extracting 7Z, no currently known installer switches dedicated to it.)
* NVIDIA FrameView SDK (No currently known installer URLs)
* NVIDIA Texture Tools Exporter (Installer is behind a login wall)
* PatrickGaskin.PulseAudio / pgaskin (Setup installer doesn't work; while the portable `pulseaudio•exe` fails with `../../src/pulseaudio/src/pulsecore/core-util.c: Secure directory creation not supported on this platform.`)
* PDFMachine (.exe is in a .zip inside a .zip)
* PHP "Test Pack" ("The package file is not a valid zip archive.")
* PHP.PHP "tests package (phpt)" ("The package file is not a valid zip archive.")
* pl4nty.winget-pkgs-selfhost (Its GitHub repo's owner stated it wasn't his app.)
* Project Diablo 2 (Apparently has the Diablo games as hard dependencies in order to be installed)
* PSAppDeployToolkit ("This application is designed to be used with the PSAppDeployToolkit PowerShell module and should not be directly invoked.")
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
* RabbitMQ (Installation fails with error 21)
* RadioDJ (Requires a very, very insecurely configured MySQL in order for a silent installation to succeed)
* RetriX ("An error occured during the app package analysis")
* Samsung.Escargot (Depends on the WebAssembly library "Walrus", for which no executables exist)
* Samsung.Odin (No widely established installer URLs)
* Scoop (No known installer URLs)
* Tavernworker (No currently known installer URLs, unless Blacksmith Launcher counts as one)
* Update Root Certificates ("The package file is not a valid zip archive.")
* USBip-win(2) (Apparently requires driver test-signing system mode?)
* Vuze ("could not create unpack process")
* Wine Gecko ("The file browser!blocklist.xml can't be installed because the file doesn't exist in the cabinet file winegecko.cab. (...)" The non-existence of MSIX/Winget support in Wine doesn't help either.)
* Wine Mono (Bafflingly tries to start a 2nd installer for a support tool before having finished the 1st installer. The 2nd installer also fails with error 2762.)
* Xensam Xearch (No known download link)
* Zygor Client (Installer is behind a login wall)
* ♪ Bluegrams.ScreenRuler (Supposedly broke repo guidelines about SourceForge)
* ♪ Command & Conquer: Red Alert 2 & Yuri's Revenge (Has the paid version of Red Alert 2 in a hardcoded folderpath as a dependency for silent installs)
* ♪ GarudaLinux.FireDragon (ARM64 version has a false positive "Can't install silently" pipeline error)
* ♪ Microsoft System Center Orchestrator Runbook Designer (Pipelines get stuck)
* ♪ Microsoft Visual C++ 2012/2013 Redistributable Arm32 (Incompatibility of the ARM64 pipelines)
* ♪ Microsoft.vcpkg (Post-installation requires a separate vcpkg-root app)
* ♪ MozillaBuild (Not all that useful, since end-users must still build the post-installation files on their own)
* ♫ EpicGames.EpicOnlineServicesSDK.C (Constantly error -2147467260)
* ♫ jklewa.ATVDesktopRemote (Requires Python 3)
* ♫ Microsoft System Center Virtual Machine Manager Client (Winget-pkgs can't silently install it)
* ♪ Microsoft.AccessibilityInsights (Its dev was pissy about it as of 2023)
* ♫ MSI NBFoundation Service (The installer at https://github.com/xchwarze/msi is clearly unofficial)
* ♫ PostGIS for PostgreSQL (Requires post-installation folder moves)
* ♫ puhitaku.mtplvcap (Requires a Nikon DSLR device to run properly)
* ♫ Sniffnet (Has Npcap as a dependency)
* ♫ WinDump (Has Npcap as dependency)
* Yamaha Vocaloid (.exe is in a .zip inside a .zip)
* Microsoft.Edge.GameAssist (Team Edge decided that MV3 was a good idea. It is not.)

## Can't be silently installed:
* `https://www•mousemux•com/files/mousemux-v2-installer.exe`
* Anything that uses InstallForge (No silent switches)
* Audeze.AudezeHQ
* AVerMedia anything
* Banking4 Home
* BenQ anything (Gets stuck on pointless VCredist installation prompt)
* BrunnerInnovation.vJoy
* Clue digital ordbok (Can't be silently installed, especially as its MSI version is fake)
* CM&V.DVBViewerDemo
* CyberLink pretty much anything
* * Ultra HD Blu-ray Advisor (`/S /v/qn` fails to make InstallShield progress silently for this app; a strange "Customer Information" prompt is possibly a factor)
* Devail1.WindowCenterResize
* Eclipso Toolbox (+ Time-expirant installer URL)
* Epson Firmware Updater
* Epson Product Setup
* ♪ EqualizerAPO(64) (Gets stuck on "Please select the devices for which Equalizer APO is to be installed.")
* ESET Online Scanner
* Final Fantasy XIV
* Fluent Store
* FreeFileSync
* Fujitsu ScanSnap Home
* GamesCleaner setup
* Genshin Impact / MiHoYo / HoYoPlay / Cognosphere
* Google WebP codec
* ♪ Artifex Software Ghostscript
* HP Universal Printer Driver / Universal Printing
* InstallForge
* Intel Memory and Storage Tool CLI
* K7 Antivirus Premium (Custom installer)
* Microsoft Remote Desktop Connection (No known silent switches)
* Microsoft.WindowsHardwareLabKit
* Mideej
* NAVER.Whale
* Nevrona Rave (Gets stuck on "You must enter your serial number.")
* ♪ Npcap
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
* Xbox main EXE (No known silent switches)
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
* Jigsaw.OutlineClient (Driver install prompt that can only be closed manually)
* IsaoMaruoka.Pixia (Silent installation fails with error 4294967292)
* Microsoft Office Subject Interface Packages for Digitally Signing VBA Projects / Sips (Gets stuck on the final prompt, "Files extracted successfully.")
* ♫ Locale Emulator
* Motorola Software Fix (Driver install prompt that can only be closed manually)
* HP Connection Optimizer (No apparent silent switches)
* VB-CABLE Virtual Audio Device (No apparent silent switches)
* Virtual AC3 Decoder (Has VB-CABLE Virtual Audio Device as a dependency)
* NextPVR (No apparent silent switches)
* Astrometa DVB-T2 Driver (Throws Error -5, "File not found", for whatever unholy reason I spent 1½ hours failing to figure out how to solve)
* Bitwarden Web Self-Hosted (Its only executable is an icons-font)
* Firefox's MSI installers (Winget fails to realise that the installation has finished)

## App is pointless:
* VLC FreeSans font (Pointless due to it being a singular GNU-available font)
* gnome.phodav (Almost certainly an outdated version of Spice.SpiceWebDAVd)
* GNU.gzip (Probably made irrelevant and extremely outdated by GnuWin32.Gzip)
* Microsoft Defender Antivirus security intelligence updates (It's only relevant for offline computers, but offline computers can't use Winget.)
* Microsoft.ShaderConductor (Pointless due to containing an outdated version of Microsoft.DirectX.ShaderCompiler)
* Microsoft.SimpleRemote (Pretty much just one big vulnerability + Depends on another and unknown app)
* Mozilla.Firefox.EMEfree (The app is completely pointless)
* ASUS XG-C100C 10G Adapter Driver (Is an older version of `aqnic650.inf`)
* McAfee Safe Connect (Will allegedly be shut down in mid-August 2026)
* ASUS PCE-BE6500 Bluetooth Driver (Is an older version of `mtkbtfilter.inf`, a.k.a. MediaTek Bluetooth Adapter)
* ASUS PCE-BE6500 Tri-band PCIe WiFi Adapter (Is an older version of `mtkwecx.inf`, a.k.a. MediaTek Wi-Fi 7 MT7925 Wireless LAN Card #6)
* Klarna Desktop App (Turned out to be such a successful phish that I myself nearly fell for it. Those guys were pros.)
* TurtleWoW (Was shut down)

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
* ♪ Microsoft ROS / Robot Operating System (Completely incomprehensible how it works)
* Microsoft SQLToolsService Migration
* Microsoft.Azure.WindowsVMAgent
* Microsoft.Delprof
* Microsoft.legacyapp
* ♫ Microsoft.PhyloD (App's purpose and commands are incomprehensible)
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
* Egyptology Extended

## All sorts of certificate errors:
|   |   |
| - | - |
| • 2fast (ZIP)<br>• ActualBudget AppX<br>• AdventurerClientJS AppX<br>• AnyFSE AppX<br>• Baulk AppX<br>• Bifrost/SamloaderKotlin MSIX<br>• BookViewer3 / BookViewerApp3 (ZIP)<br>• chARpack AppX<br>• Cynnexis Tide MSIX<br>• FluentFlyouts (MSIXBundle)<br>• Flycast AppX<br>• gabboxl.FluentWeather (MSIXBundle)<br>• Gorilla UI<br>• HDRImageViewer (ZIP)<br>• Hiddify MSIX<br>• Houseclub FrayxRulez (MSIXBundle)<br>• Intag MSIX<br>• IRCameraView (ZIP)<br>• KeePassPasskey (ZIP)<br>• Kodi MSIX<br>• LibreWolf MSIX | • LRReader (MSIXBundle)<br>• Microsoft eBPF for Windows - MSI (Doesn't have a valid signature... in an MSI file)<br>• Microsoft.SensorExplorer / busiotools (MSIXBundle)<br>• Mockoon AppX<br>• Mélodie Feugy AppX<br>• Ossia Score AppXBundle<br>• Passbolt (ZIP)<br>• RetroArch AppX<br>• RevoltChat AppX<br>• SimpleWeather (MSIXBundle)<br>• TasksORG MSIX<br>• TheElixZammuto Moonlight UWP (MSIXBundle)<br>• TouchXRPT (ZIP)<br>• Tracky-Mouse MSIX<br>• UltraPad/RectifyPad MSIX<br>• underpig1 Octos MSIX<br>• Unpaint (Running it portably throws "MSVCP140_ATOMIC_WAIT_APP.dll not found")<br>• VideoLAN.VLC-UWP (Also lacks "SharedLibrary.dll", etc.)<br>• WebcamOnDesktop (MSIXBundle)<br>• Wino Mail (MSIXBundle)<br>• XBSX2 (MSIXBundle)<br>• Bitwarden MSIX<br>• Raycast (Running it portably crashes on launch)

## Time-expirant installer URLs:
* 3DMark (≤ 3min)
* ASUS anything on rog•asus•com (Fixable by changing the URL to `dlcdnets`)
* Azure VPN Client (Version on appcenterMS has time-expirant installer URLs)
* BlackBerry Access (≤ 5min)
* Citrix DeviceTrust Client Extension
* Cricut Design Space (〜60min)
* Game Jolt anything (24 hours)
* ItchIO anything except its main client (1min)
* Nvidia.Nsight.Systems (〜30min)
* Panda3DS' nightly builds
* Realtek anything (5min)
* Splice Instrument (1min)
* McAfee WebAdvisor (3〜6 days)
* Syrinscape Online
* Readwise Reader

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
* AMD Software: Adrenalin Edition ("Download Not Complete" anti-"external access" measures)
* download-center•epson•com
* AltDVB

## Self-extracting 7Z-s disguised as .exe-s:
* Microsoft Endpoint Community Manager (Self-extracting 7Z)
* Microsoft Keyboard Layout Creator (Setup .exe-/.msi-s inside self-extracting 7Z)
* ZohoCRM (Self-extracting 7Z)

## "No supported installer(s) found in zip archive.":
|   |   |
| - | - |
| • Apache Maven<br>• DirectoryLister<br>• dxwrapper (elishacloud)<br>• FineFTP Server<br>• GNOME "atk", "gail", "gnome-common", "gnome-vfs", "goocanvas",<br>"gtkhtml", "gtksourceview", "intltool", "libcroco", and "libglade"<br>• GoldSrcModelThumbnailProvider<br>• Google.re2<br>• Gradle Distributions<br>• KeeperSecurity keeper-sdk-dotnet / PowerCommander<br>• kemnnx64<br>• Kotlin Language Server<br>• LazyDuchess.MonoPatcher<br>• LazyDuchess.TS2-Extender<br>• libsdl-org.SDL<br>• Microsoft QDK Samples<br>• Microsoft React Native WinRT<br>• Microsoft UEFI Debug Tools<br>• Microsoft.FactoryOrchestrator Service<br>• Microsoft.vc-ue-extensions<br>• Microsoft.Windows-appsample-marble-maze | • Microsoft.Windows-appsample-photo-editor<br>• Microsoft winget-cli-restsource<br>• Mozilla CrashReporter Symbols<br>• Npcap SDK<br>• NVDA Controller Client<br>• NVIDIA.CCCL<br>• OpenBIOS.OpenBIOS<br>• pascatl.ha-dhl<br>• PHP.PHP "Development package (SDK to develop PHP extensions)"<br>• PHP.PHP Debug Pack<br>• Pixel Streaming Infrastructure<br>• SignPath.CryptoProviders.Cryptoki<br>• simdjson singleheader<br>• Tiny UI Fix for The Sims 3<br>• Ultimate ASI Loader<br>• WebView2Browser<br>• windows-heic-thumbnails<br>• zlib<br>• Microsoft.OnnxRuntime<br>• Atola MultiDrive WinPE<br>• Enhanced-GPU-PV<br>• worproject "storage_v4", "aicwlan_arm64", and "rpi5-uefi"<br>• iTerm2

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
* ♪ Bol-van's builds of Zapret2 (Avira/Avast false positives; https://github.com/microsoft/winget-pkgs/pull/375864#issuecomment-4477591311)
* Dinger.RDHost (ESET false positive)
* łzbench (A likely false positive detection by ESET)

## Will likely work, but Wingetcreate throws "Failed to parse the package from" and I'm tired:
* BabelPad
* BabelMap
* GhostPCL
* GhostXPS

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
* LibRetro Ludo (Ugly logo)
* Meld Spark Plugin for OBS (I'm too old for Aİ-functions-only stuff)
* AntiCheatExpert (Tencent/PRC app)
* PiMon (PRC app)
