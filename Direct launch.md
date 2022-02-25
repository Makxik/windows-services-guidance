# Test configuration 1
With all services below disabled: <span style="color:red">doesn't boot.</span>
<details>
  <summary>REG.exe agg...</summary>
  /v "Start" /t reg_dword /d 4 /f<br />
  WdNisSvc failed<br />
  WinDefend failed<br />
</details>

Explanation of columns | Key (internal) name of the service | Microsoft recommendation/advice about disabling this service on Windows Server 2016 in a typical, well-managed enterprise deployment and where the server is not being used as an end-user desktop replacement.
--- | --- | ---
ActiveX Installer (AxInstSV) | AxInstSV | OK to disable
AllJoyn Router Service | AJRouter | No guidance
App Readiness | AppReadiness | Do not disable
Application Identity | AppIDSvc | No guidance
Application Information | Appinfo | No guidance
Application Layer Gateway Service | ALG | No guidance
Application Management | AppMgmt | No guidance
AppX Deployment Service (AppXSVC) | AppXSvc | No guidance
Auto Time Zone Updater | tzautoupdate | Already disabled
Background Intelligent Transfer Service | BITS | No guidance
Background Tasks Infrastructure Service | BrokerInfrastructure | No guidance
Base Filtering Engine | BFE | No guidance
Bluetooth Support Service | bthserv | OK to disable
CDPUserSvc | CDPUserSvc | OK to disable
Certificate Propagation | CertPropSvc | No guidance
Client License Service (ClipSVC) | ClipSVC | No guidance
CNG Key Isolation | KeyIso | No guidance
COM+ Event System | EventSystem | No guidance
COM+ System Application | COMSysApp | No guidance
Computer Browser | Browser | Already disabled
Connected Devices Platform Service | CDPSvc | No guidance
Connected User Experiences and Telemetry | DiagTrack | No guidance
Contact Data | PimIndexMaintenanceSvc | OK to disable
CoreMessaging | CoreMessagingRegistrar | No guidance
Credential Manager | VaultSvc | No guidance
Cryptographic Services | CryptSvc | No guidance
Data Sharing Service | DsSvc | No guidance
DataCollectionPublishingService | DcpSvc | No guidance
DCOM Server Process Launcher | DcomLaunch | No guidance
Device Association Service | DeviceAssociationService | No guidance
Device Install Service | DeviceInstall | No guidance
Device Management Enrollment Service | DmEnrollmentSvc | No guidance
Device Setup Manager | DsmSvc | No guidance
DevQuery Background Discovery Broker | DevQueryBroker | No guidance
DHCP Client | Dhcp | No guidance
Diagnostic Policy Service | DPS | No guidance
Diagnostic Service Host | WdiServiceHost | No guidance
Diagnostic System Host | WdiSystemHost | No guidance
Distributed Link Tracking Client | TrkWks | No guidance
Distributed Transaction Coordinator | MSDTC | No guidance
dmwappushsvc | dmwappushservice | OK to disable
DNS Client | Dnscache | No guidance
Downloaded Maps Manager | MapsBroker | OK to disable
Embedded Mode | embeddedmode | No guidance
Encrypting File System (EFS) | EFS | No guidance
Enterprise App Management Service | EntAppSvc | No guidance
Extensible Authentication Protocol | EapHost | No guidance
Function Discovery Provider Host | fdPHost | No guidance
Function Discovery Resource Publication | FDResPub | No guidance
Geolocation Service | lfsvc | OK to disable
Group Policy Client | gpsvc | No guidance
Human Interface Device Service | hidserv | No guidance
HV Host Service | HvHost | Do not disable
Hyper-V Data Exchange Service | vmickvpexchange | Do not disable
Hyper-V Guest Service Interface | vmicguestinterface | Do not disable
Hyper-V Guest Shutdown Service | vmicshutdown | Do not disable
Hyper-V Heartbeat Service | vmicheartbeat | Do not disable
Hyper-V PowerShell Direct Service | vmicvmsession | Do not disable
Hyper-V Remote Desktop Virtualization Service | vmicrdv | Do not disable
Hyper-V Time Synchronization Service | vmictimesync | Do not disable
Hyper-V Volume Shadow Copy Requestor | vmicvss | Do not disable
IKE and AuthIP IPsec Keying Modules | IKEEXT | No guidance
Interactive Services Detection | UI0Detect | No guidance
Internet Connection Sharing (ICS) | SharedAccess | OK to disable
IP Helper | iphlpsvc | No guidance
IPsec Policy Agent | PolicyAgent | No guidance
KDC Proxy Server service (KPS) | KPSSVC | No guidance
KtmRm for Distributed Transaction Coordinator | KtmRm | No guidance
Link-Layer Topology Discovery Mapper | lltdsvc | OK to disable
Local Session Manager | LSM | No guidance
Microsoft (R) Diagnostics Hub Standard Collector | diagnosticshub.standardcollector.service | No guidance
Microsoft Account Sign-in Assistant | wlidsvc | OK to disable
Microsoft App-V Client | AppVClient | Already disabled
Microsoft iSCSI Initiator Service | MSiSCSI | Do not disable
Microsoft Passport | NgcSvc | OK to disable
Microsoft Passport Container | NgcCtnrSvc | OK to disable
Microsoft Software Shadow Copy Provider | swprv | No guidance
Microsoft Storage Spaces SMP | smphost | Do not disable
Net.Tcp Port Sharing Service | NetTcpPortSharing | Already disabled
Netlogon | Netlogon | No guidance
Network Connection Broker | NcbService | OK to disable
Network Connections | Netman | No guidance
Network Connectivity Assistant | NcaSvc | No guidance
Network List Service | netprofm | No guidance
Network Location Awareness | NlaSvc | No guidance
Network Setup Service | NetSetupSvc | No guidance
Network Store Interface Service | nsi | No guidance
Offline Files | CscService | Already disabled
Optimize drives | defragsvc | No guidance
Performance Counter DLL Host | PerfHost | No guidance
Performance Logs & Alerts | pla | No guidance
Phone Service | PhoneSvc | OK to disable
Plug and Play | PlugPlay | No guidance
Portable Device Enumerator Service | WPDBusEnum | No guidance
Power | Power | No guidance
Print Spooler | Spooler | OK to disable if not a print server or a DC
Printer Extensions and Notifications | PrintNotify | OK to disable if not a print server
Problem Reports and Solutions Control Panel Support | wercplsupport | No guidance
Program Compatibility Assistant Service | PcaSvc | OK to disable
Quality Windows Audio Video Experience | QWAVE | OK to disable
Radio Management Service | RmSvc | OK to disable
Remote Access Auto Connection Manager | RasAuto | No guidance
Remote Access Connection Manager | RasMan | No guidance
Remote Desktop Configuration | SessionEnv | Do not disable
Remote Desktop Services | TermService | Do not disable
Remote Desktop Services UserMode Port Redirector | UmRdpService | Do not disable
Remote Procedure Call (RPC) | RpcSs | No guidance
Remote Procedure Call (RPC) Locator | RpcLocator | No guidance
Remote Registry | RemoteRegistry | Do not disable
Resultant Set of Policy Provider | RSoPProv | No guidance
Routing and Remote Access | RemoteAccess | Already disabled
RPC Endpoint Mapper | RpcEptMapper | No guidance
Secondary Logon | seclogon | No guidance
Secure Socket Tunneling Protocol Service | SstpSvc | Do not disable
Security Accounts Manager | SamSs | Do not disable
Sensor Data Service | SensorDataService | OK to disable
Sensor Monitoring Service | SensrSvc | OK to disable
Sensor Service | SensorService | OK to disable
Server | LanmanServer | Do not disable
Shell Hardware Detection | ShellHWDetection | OK to disable
Smart Card | SCardSvr | Already disabled
Smart Card Device Enumeration Service | ScDeviceEnum | OK to disable
Smart Card Removal Policy | SCPolicySvc | No guidance
SNMP Trap | SNMPTRAP | No guidance
Software Protection | sppsvc | No guidance
Special Administration Console Helper | sacsvr | No guidance
Spot Verifier | svsvc | No guidance
SSDP Discovery | SSDPSRV | OK to disable
State Repository Service | StateRepository | No guidance
Still Image Acquisition Events | WiaRpc | OK to disable
Storage Service | StorSvc | No guidance
Storage Tiers Management | TieringEngineService | No guidance
Superfetch | SysMain | No guidance
Sync Host | OneSyncSvc | OK to disable
System Event Notification Service | SENS | No guidance
System Events Broker | SystemEventsBroker | Do not disable
Task Scheduler | Schedule | No guidance
TCP/IP NetBIOS Helper | lmhosts | No guidance
Telephony | TapiSrv | Do not disable
Themes | Themes | Do not disable
Tile Data model server | tiledatamodelsvc | Do not disable
Time Broker | TimeBrokerSvc | Do not disable
Touch Keyboard and Handwriting Panel Service | TabletInputService | OK to disable
Update Orchestrator Service for Windows Update | UsoSvc | Do not disable
UPnP Device Host | upnphost | OK to disable
User Access Logging Service | UALSVC | No guidance
User Data Access | UserDataSvc | OK to disable
User Data Storage | UnistoreSvc | OK to disable
User Experience Virtualization Service | UevAgentService | Already disabled
User Manager | UserManager | No guidance
User Profile Service | ProfSvc | No guidance
Virtual Disk | vds | No guidance
Volume Shadow Copy | VSS | No guidance
WalletService | WalletService | OK to disable
Windows Audio | Audiosrv | OK to disable
Windows Audio Endpoint Builder | AudioEndpointBuilder | OK to disable
Windows Biometric Service | WbioSrvc | No guidance
Windows Camera Frame Server | FrameServer | OK to disable
Windows Connection Manager | Wcmsvc | No guidance
Windows Defender Network Inspection Service | WdNisSvc | No guidance
Windows Defender Service | WinDefend | No guidance
Windows Driver Foundation - User-mode Driver Framework | wudfsvc | No guidance
Windows Encryption Provider Host Service | WEPHOSTSVC | No guidance
Windows Error Reporting Service | WerSvc | Do not disable
Windows Event Collector | Wecsvc | Do not disable
Windows Event Log | EventLog | No guidance
Windows Firewall | MpsSvc | No guidance
Windows Font Cache Service | FontCache | No guidance
Windows Image Acquisition (WIA) | stisvc | OK to disable
Windows Insider Service | wisvc | OK to disable
Windows Installer | msiserver | No guidance
Windows License Manager Service | LicenseManager | No guidance
Windows Management Instrumentation | Winmgmt | No guidance
Windows Mobile Hotspot Service | icssvc | OK to disable
Windows Modules Installer | TrustedInstaller | No guidance
Windows Push Notifications System Service | WpnService | OK to disable
Windows Push Notifications User Service | WpnUserService | OK to disable
Windows Remote Management (WS-Management) | WinRM | Do not disable
Windows Search | WSearch | Already disabled
Windows Time | W32Time | No guidance
Windows Update | wuauserv | No guidance
WinHTTP Web Proxy Auto-Discovery Service | WinHttpAutoProxySvc | Do not disable
Wired AutoConfig | dot3svc | No guidance
WMI Performance Adapter | wmiApSrv | No guidance
Workstation | LanmanWorkstation | No guidance
Xbox Live Auth Manager | XblAuthManager | Should be disabled
Xbox Live Game Save | XblGameSave | Should be disabled
