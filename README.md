
![Capture](https://github.com/user-attachments/assets/d4c64806-0318-4db2-b9f5-e782c63ea130)
# Divulge-Stealer
Divulge Stealer a highly advanced info-stealer that outperforms its predecessor, Umbral-Stealer by Blank-c. This new iteration is a complete overhaul with enhanced capabilities, targeting 25 major cryptocurrency wallets with precision.

What’s New in Divulge Stealer:
1. Comprehensive Redesign: Divulge Stealer has been meticulously reworked from the ground up. Building on the foundation of Umbral-Stealer, it introduces advanced capabilities for targeting cryptocurrency wallets with unprecedented accuracy.

2. Expanded Wallet Support: Our stealer now supports 25 major cryptocurrency wallets, including well-known names like Bitcoin, Ethereum, and Monero. This expansion ensures a broader reach and higher effectiveness in data extraction.

3. Recursive Data Extraction: Utilizing a sophisticated recursive technique, Divulge Stealer ensures thorough scanning and retrieval of wallet files, leaving no trace behind.

4. Signature Appending Feature: In a notable upgrade, the new build includes a feature allowing you to append another .exe digital signature upon compilation. This adds a layer of customization and stealth, making detection even more challenging.

5. Optimized: Removed useless features to make the overall output file much smaller.

# Key Features:

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



# Terms of Service (TOS) for Divulge Stealer (Developed by Py_Dev)


1. Acknowledgement of Research Purpose 
The Divulge Stealer software is created solely for research, testing, and educational purposes. It is intended only for use in virtual machines or test environments. Any use of this software outside of these clearly defined settings is strictly prohibited. By using this software, you acknowledge and agree to adhere to these conditions.

2. No Liability
As the developer (Py_Dev), I disclaim any and all liability for any direct, indirect, incidental, or consequential damages that may result from the use, misuse, or inability to use the Divulge Stealer software. This includes, but is not limited to, loss of data, financial loss, security breaches, or any other harms. Py_Dev shall not be held responsible for any illegal or unethical use of this software, and the responsibility for compliance with applicable laws rests solely with the user.

3. Prohibition of Unauthorized Usage
Divulge Stealer is provided as a tool for research and should not be used in any production or live environments. You are required to use this tool solely within isolated, controlled, and non-public environments, such as virtual machines. Any application of Divulge Stealer for the purposes of unauthorized access, data theft, or illegal activities is strictly forbidden. Failure to comply with this may result in legal consequences, and Py_Dev is not responsible for the actions of the user.

4. No Warranties
This software is provided "as is," without any express or implied warranties, including but not limited to warranties of merchantability, fitness for a particular purpose, or non-infringement. I, Py_Dev, make no guarantees that the software will be free of bugs, errors, or vulnerabilities, or that it will function as expected in all test scenarios.

5. Indemnity
By using Divulge Stealer, you agree to indemnify and hold harmless Py_Dev from any claims, liabilities, damages, losses, or legal proceedings that may arise as a result of the misuse or unlawful use of this software. This includes, but is not limited to, any legal or regulatory actions brought against you due to violations of laws or policies regarding data security, privacy, or unauthorized access.

6. Anti-VM and Use Restriction Notice
This software includes an Anti-Virtual Machine Detection feature that prevents its use in certain environments. Despite this, you must ensure that the software is executed only within a virtual machine or test environment. Any activation of this software on a live system, without the explicit authorization of the system owner, is strictly prohibited and considered unlawful.

7. Amendments and Modifications
Py_Dev reserves the right to modify or update this Terms of Service at any time. Continued use of the software after any modifications constitutes acceptance of the revised terms.

8. Governing Law
This TOS shall be governed and construed in accordance with the laws of the jurisdiction where THE USER operates.

By using Divulge Stealer, you affirm that you have read, understood, and agreed to these terms. Any violation of these terms may result in termination of your rights to use this software and potential legal action.


Credits to: https://github.com/Blank-c
