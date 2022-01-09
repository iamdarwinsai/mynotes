# Nmap Switches

* -sS  **stealth scan**
* -sT  **TCP SCAN**
* -sU  **UDP SCAN**
* -O   **Detects the target OS**
* -sn  **Tells us wether the host is up or down, in other words it provides PING**
* -oA **Saves the output in all the 3 formats**
* -oG **Saves the output in grepable format**
* -oN **Saves the output in normal foramt**
* -p  **Scans the port**
* -p- **Scans all the ports**
* --script **To activate script**


# NSE SCRIPTS
* --script=vuln **to find vuln**
* --script=safe **wot affect th target**
* --script=intrusive **affects the target**
* --script=exploit **exploits th vuln**
* --script=auth **attmpt to bypass authentication**
* --script=brute **bruteforce the credenstials**

> Nmap stores its scripts on linux at **/usr/share/nmap/scripts**