## Kautilya

### Kautilya is a toolkit which provides various payloads for a Human Interface Device which may help in breaking in a computer during penetration tests. 
By [facebook](https://www.facebook.com/Gihad.Metasploit)

##### List of Payloads
##### Windows
###### Gather
- Gather Information
- Hashdump and Exfiltrate
- Keylog and Exfiltrate
- Sniffer
- WLAN keys dump
- Get Target Credentials
- Dump LSA Secrets
- Dump passwords in plain
- Copy SAM
- Dump Process Memory
- Dump Windows Vault Credentials

###### Execute
- Download and Execute
- Connect to Hotspot and Execute code
- Code Execution using Powershell
- Code Execution using DNS TXT queries
- Download and Execute PowerShell Script
- Execute ShellCode
- Reverse TCP Shell

###### Backdoor
- Sethc and Utilman backdoor
- Time based payload execution
- HTTP backdoor
- DNS TXT Backdoor
- Wireless Rogue AP
- Tracking Target Connectivity
- Gupt Backdoor

###### Escalate
- Remove Update
- Forceful Browsing

###### Manage
- Add an admin user
- Change the default DNS server
- Edit the hosts file
- Add a user and Enable RDP
- Add a user and Enable Telnet
-  Add a user and Enable Powershell Remoting

###### Drop Files
- Drop a MS Word File
- Drop a MS Excel File
- Drop a CHM (Compiled HTML Help) file
- Drop a Shortcut (.LNK) file
- Drop a JAR file

###### Misc
- Browse and Accept Java Signed Applet
- Speak on Target

##### Linux
- Download and Execute
- Reverse Shells using built in tools
- Code Execution
- DNS TXT Code Execution
- Perl reverse shell (MSF)

##### OSX
- Download and Execute
- DNS TXT Code Execution
- Perl Reverse Shell (MSF)
- Ruby Reverse Shell (MSF)


##### Payloads Compatibility
- The Windows payloads and modules are written mostly in powershell (in combination with native commands) and are tested on Windows 7 and Windows 8. 

- The Linux payloads are mostly shell scripts (those installed by default) in combination with commands. These are tested on Ubuntu 11.

- The OS X payloads are shell scripts (those installed by default) with usage of native commands. Tested on OS X Lion running on a VMWare

##### Usage
Run kautilya.rb and follow the menus. Kautilya asks for your inputs for various options. The generated payload is copied to the output directory of Kautilya.

The generated payload is an arduino sketch, ready to be used with Arduino IDE. Burn it to Human Interface Device of your choice and have fun!


##### Bugs and Feature requests
Raise an issue or post to the google group.

##### Dependencies
Kautilya needs colored, highline and artii (and win32console on Windows) gems. Use

bundle install


##### Credits
Due Credits and Borrowed Code: I do not put credits of any borrowed code inside the payloads generated by Kautilya to save space. Credits and thanks are generally mentioned either in the description of payloads or accompanying blog post. If you think I missed any due credit, please let me know. I will add the credits with apologies.

