# Attack-Defend-Lab

## Objective
- The objective of this exercise is to simulate a real-world attack/defend environment
- We use a Meterpreter reverse TCP payload initiated by the attack machine (Kali) and have the victim machine affected with the malware
- Through this exercise, we can see what actions a bad actor can take once they have access to a victim’s machine, either obtaining a users own personal info or a larger company's database assets

## Skills Learned
- Learning to save snapshots in a VM environment in scenarios where things get broken
- Minimizing risk of not allowing the entry of malware from the VM to my host machine by configuring network settings to an internal network between hypervisors
- How to initiate a payload using Meterpreter
- Create an HTTP server using python3

## Tools Used
- Windows 10 Version 22H2 as Victim Machine
- Kali Linux 2025.2 as Attack Machine
- Nmap For Reconnaissance
- Metasploit used Msfconsole to look for Vulnerabilities on the Victim
- Meterpreter
- Python to Create the HTTP Server

## Steps (Screenshots)
<img width="1024" height="768" alt="VirtualBox_HomeLab_01_09_2025_10_35_59" src="https://github.com/user-attachments/assets/39dc6295-6706-44c3-b836-bf81a6d454aa" />
<img width="800" height="600" alt="VirtualBox_kali-linux-2025 2-virtualbox-amd64_01_09_2025_19_12_18" src="https://github.com/user-attachments/assets/1c007ff5-4cb7-40dc-b5d3-6fc3ed4045d8" />

Ref 1, 2: Windows + Linux Downloading


<img width="1024" height="768" alt="VirtualBox_HomeLab_04_09_2025_23_08_33" src="https://github.com/user-attachments/assets/5b92f2f4-ca16-4491-adcd-51b10c756bdc" />

Ref 3: Configuring Networks (Windows)


<img width="1920" height="945" alt="VirtualBox_kali-linux-2025 2-virtualbox-amd64_30_09_2025_20_16_43" src="https://github.com/user-attachments/assets/a458de88-e374-43b2-bbd3-59e173a3c0af" />

Ref 4: Ran a Nmap scan On my Windows IP- we see a traceroute


<img width="1920" height="945" alt="VirtualBox_kali-linux-2025 2-virtualbox-amd64_30_09_2025_22_12_46" src="https://github.com/user-attachments/assets/4f474e30-3554-4858-a9a2-f50e59c95a47" />

Ref 5: Used Msfvenom to list out all payloads


<img width="1920" height="945" alt="VirtualBox_kali-linux-2025 2-virtualbox-amd64_30_09_2025_22_19_13" src="https://github.com/user-attachments/assets/27b1568b-0dd3-496a-b5e2-2d8db3c4d95a" />

Ref 6: Selecting the payload of my choice- Meterpreter reverse TCP


<img width="888" height="818" alt="VirtualBox_kali-linux-2025 2-virtualbox-amd64_01_10_2025_21_02_27" src="https://github.com/user-attachments/assets/9e63ae4f-cef9-42cd-8d50-13128a1487f1" />

Ref 7: Creating the HTTP server


<img width="1024" height="768" alt="VirtualBox_HomeLab_01_10_2025_21_13_48" src="https://github.com/user-attachments/assets/21813b50-6d3b-4dea-b953-b0b2cf6c4a07" />

Ref 8: Dowloading the file in its entirety- file name is rev.exe


<img width="888" height="818" alt="VirtualBox_kali-linux-2025 2-virtualbox-amd64_01_10_2025_21_38_40" src="https://github.com/user-attachments/assets/c7ccabbc-ac7c-4442-bcab-51c658c84854" />

Ref 9: Using Meterpreter and achieving a successful connection


<img width="888" height="818" alt="VirtualBox_kali-linux-2025 2-virtualbox-amd64_01_10_2025_21_45_26" src="https://github.com/user-attachments/assets/5f086c8e-8eb3-4b47-ae03-6e303782aa2b" />

Ref 10: Testing commands once we have access- things like sysinfo and screenshot are very intrusive

