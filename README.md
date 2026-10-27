QOSami Activation & Deployment Scripts (QOS-MAS)
מערכת הפעלה ואוטומציה מקומית עבור Windows ו-Office בניהול הארכיטקט Toura Sami TaxiDriver (taxidriver247).

תומכת בשיטות HWID, Ohook, TSforge, ו-Online KMS מתוך סביבת ה-PowerShell הראשית.

Identity & Security Seal
Operator / Architect: Toura Sami TaxiDriver (taxidriver247)

System Signature: SIGNED_BY_TS | Seal: 4764bd1aeca08c38 | DNA: [1,3,3,7]

Primary Node: Windows 11 / Server (Admin PowerShell)

Master Projects Directory: F:\QOSAMI_PROJECTS\ / D:\QOSAMI_CORE_OS\

How to Activate Windows / Office / Extended Security Updates (ESU)?
Method 1 - PowerShell (Recommended) ❤️
Click the Start Menu, type PowerShell, and open it as Administrator.

Copy and paste the code below and press Enter:

For Windows 8.1, 10, 11 and Windows Server:

PowerShell
irm https://get.activated.win | iex
If the above is blocked (by ISP/DNS), try this (needs updated Windows 10 or 11):

PowerShell
iex (curl.exe -s --doh-url https://1.1.1.1/dns-query https://get.activated.win | Out-String)
Script not launching? Use Method 2 below.

In the menu that appears, type the number corresponding to one of the Green options (HWID for Windows 10/11, Ohook for Office).

Method 2 - Traditional (Windows Vista and later / Offline Mode)
Download or locate the script file:

MAS_AIO.cmd (Direct script)

MAS_AIO.zip (If the direct script is blocked by your security settings)

Place the file in your master workspace:

F:\QOSAMI_PROJECTS\Tools\MAS_AIO.cmd

Right-click MAS_AIO.cmd and select Run as Administrator.

In the menu that appears, type the number corresponding to one of the Green options.

[!TIP]
Some ISPs/DNS providers block direct connection to domains. You can bypass this by enabling DNS-over-HTTPS (DoH) in your browser or local mesh routers (Cudy P5 / Archer C80).

[!NOTE]
The irm (Invoke-RestMethod) command in PowerShell downloads a script from a specified URL, and the iex (Invoke-Expression) command executes it directly in memory.

Always verify execution sources and SHA256 signatures before running scripts in elevated Administrator mode.

Maintain internal backup copies inside F:\QOSAMI_PROJECTS\ for offline node provisioning.