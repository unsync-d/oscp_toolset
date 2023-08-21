# oscp_toolset
Tools I created or modified while studying for OSCP
## go_nmap.sh
This is a modified version of the tool developed by **@21y4d** at https://github.com/21y4d/nmapAutomator. 
### Features
- All of the capabilities of the original tool from **@21y4d**.
- It prints the concrete nmap command executed during each phase.
- The UDP scan loading bar works properly.
- It performs recon on FTP (at port 21) with **medusa**. It uses **/usr/share/seclists/Usernames/top-usernames-shortlist.txt** for usernames and a merge of **/usr/share/seclists/Passwords/Common-Credentials/top-20-common-SSH-passwords.txt** and **/usr/share/seclists/Passwords/Common-Credentials/top-passwords-shortlist.txt** for passwords.
