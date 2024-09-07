# Divulge-Stealer
Divulge Stealer a highly advanced info-stealer that outperforms its predecessor, Umbral-Stealer by Blank-c. This new iteration is a complete overhaul with enhanced capabilities, targeting 25 major cryptocurrency wallets with precision.

What’s New in Divulge Stealer:
1. Comprehensive Redesign: Divulge Stealer has been meticulously reworked from the ground up. Building on the foundation of Umbral-Stealer, it introduces advanced capabilities for targeting cryptocurrency wallets with unprecedented accuracy.

2. Expanded Wallet Support: Our stealer now supports 25 major cryptocurrency wallets, including well-known names like Bitcoin, Ethereum, and Monero. This expansion ensures a broader reach and higher effectiveness in data extraction.

3. Recursive Data Extraction: Utilizing a sophisticated recursive technique, Divulge Stealer ensures thorough scanning and retrieval of wallet files, leaving no trace behind.

4. Signature Appending Feature: In a notable upgrade, the new build includes a feature allowing you to append another .exe digital signature upon compilation. This adds a layer of customization and stealth, making detection even more challenging.

5. Optimized: Removed useless features to make the overall output file much smaller.

Key Features:
Spoiler (Click to Hide)

Anti-Virtual Machine Detection:
Detects and exits if running in a virtual machine to avoid analysis in controlled environments.
Ensures execution only on legitimate systems by integrating with the AntiVM component.

Admin Privileges Management:
Requests elevated privileges if needed for certain operations like disabling security mechanisms or accessing restricted areas of the system.
Automatically adds itself to startup if configured, ensuring persistence across reboots.

Self-Protection Mechanisms:
The payload uses techniques like hiding its own executable and excluding itself from Windows Defender scans.
Windows Defender is disabled to avoid detection during runtime.

Data Collection:
Browser Passwords: Extracts credentials stored in major browsers.
Browser Cookies: Hijacks sessions for further access.
Google Chrome
Brave
Chromium-based browsers
Microsoft Edge
Opera (and Opera GX)
Yandex
Vivaldi
Comodo
Epic Privacy Browser, and more..

Discord Token Stealing: Extracts tokens from Discord sessions to compromise user accounts.
Cryptocurrency Wallet Theft: Scans the system for installed cryptocurrency wallets and attempts to steal private keys and wallet data.
Screenshot Capturing: Captures screenshots of the desktop environment for further insights into user activities.
Saved Credit Cards: Retrieves stored credit card information.
System Information: Gathers detailed system data including IP, OS version, Anti-Virus, and hardware details.




Wallets
Bitcoin Core (wallets folder)
Armory
Bytecoin
Ethereum (Keystore and Wallet Files)
Litecoin
Dash
Dogecoin
ZCash
Monero
Ripple
Stellar
Binance
Tron
VeChain
Polkadot
Cardano
Tezos
Zilliqa
Neo
Jaxx Liberty (com.liberty.jaxx)
Exodus (exodus.wallet)
Electrum (wallets)
Atomic Wallet (Local Storage)
Guarda Wallet (Local Storage)
Coinomi

Real-Time Connection Monitoring:
Monitors for an active internet connection before executing any network-related tasks, ensuring data exfiltration can be completed successfully.

Exfiltration of Stolen Data:
Compresses collected data (credentials, cookies, screenshots, wallets) into a single archive and sends it to a specified webhook using the Postman component.
Sends statistical information on the number of credentials, cookies, and other items successfully stolen.

Stealth Operations:
The payload can operate silently without user interaction or visible signs of execution.
Optional functionality for removing itself from the system after execution, leaving no trace behind.

Blocking Security Sites:
Blocks access to well-known antivirus and security websites (e.g., VirusTotal, Avast, McAfee) to prevent users from uploading the payload for analysis or removing threats from the system.
