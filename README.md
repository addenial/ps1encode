ps1encode
=========
#### Use to generate and encode a powershell based metasploit payloads.

Writen by Piotr Marszalik - @addenial - peter.mars[at]outlook.com
-  orginal version - 05/08/2013

Available output types:
- raw (plaintext powershell payload only - no base64 encoding)
- cmd (for use with bat files)
- vba (for use with macro trojan docs)
- vbs (for use with vbs scripts)
- war (tomcat)
- exe (executable) requires MinGW - x86_64-w64-mingw32-gcc [apt-get install mingw-w64]
- go (golang executable) requires Golang - go [apt-get install golang-go]
- java (for use with malicious java applets)
- js (javascript)
- js-rd32 (javascript called by rundll32.exe)
- php (for use with php pages)
- hta (HTML applications)
- cfm (for use with Adobe ColdFusion)
- aspx (for use with Microsoft ASP.NET)
- lnk (windows shortcut - requires a webserver to stage the payload)
- sct (COM scriptlet - requires a webserver to stage the payload)


~~Powershell code based on PowerSploit written by Matthew Graeber and SET by Dave Kennedy~~

Latest version using modified msfvenom psh-cmd template with added obfuscation (XOR shellcode, etc.)

DETAILS:
* https://rvnsec.wordpress.com/2014/09/01/ps1encode-powershell-for-days/
* https://rvnsec.wordpress.com/2015/12/18/shell-party-continues/

