# RockyouMask
A Mask-Attack using hashcat based on the rockyou leak

This program works crossplatform Windows - Linux as long as you have python and hashcat installed

python:
  Linux: sudo apt install python
  Windows: https://www.microsoft.com/en-us/p/python-38/9mssztt1n39l?activetab=pivot:overviewtab

hashcat:
  Linux: sudo apt-get install hashcat
  Windows: https://hashcat.net/files/hashcat-5.1.0.7z

On Windows put your hashes in a text file (one hash per line) in the hashcat directory
On Linux put your hashes in a text file where you excecute the script

cracked hashes:
  Linux: hashcat yourhashfilehere --show
  
  Windows: in the commandline navigateto the hashcat directory - .\hashcat64.exe yourhashfilehere --show

Running a Radeon RX 570 this script can bruit-force 70% of passwords in rockyou in about half a day, 60% in about half an hour
