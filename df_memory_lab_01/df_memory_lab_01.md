# Memory Forenics Lab 01 - student version

[Memory Dump Files](https://hogeschoolpxl-my.sharepoint.com/:u:/g/personal/20004162_pxl_be/EbQ5TIOcEgZEiwYkWWBXH5wBpwKI26_ECir82PF-nElDBg?e=glbbmd)

[PXL Memory Forensics Intro 25](https://tryhackme.com/room/memoryforensicsll01)

## Case 1 - Trojan Adobe

Your Security Operations Center (SOC) has collected a memory dump from an isolated endpoint suspected of being infected with a banking trojan disguised as an Adobe document. Your task is to apply your expertise in threat intelligence and reverse engineering to conduct memory forensics on this compromised system.

You have also been alerted about a potentially malicious IP address associated with the file: 41.168.5.140.

The memory dump file: trojan_adobe.vmem.

### Case 1 - Questions

Based on the memory dump file, answer the following questions:

1. __What is the build version of the host machine?__

2. __At what time was the memory file acquired?__

3. __What process can be considered suspicious?__

4. __What is the parent process of the suspicious process?__

5. __What is the PID of the suspicious process?__

6. __What is the parent process PID?__

7. __What user-agent was employed by the adversary?__

8. __Was Chase one of the suspicious bank domains? (Y/N)?__

## Case 2 - Ransomware Investigation

You've been notified that your company has experienced a series of ransomware attacks that have been targeting organizations worldwide. While your team has successfully obtained the decryption key and recovered from the incident, your responsibility is to conduct a post-incident review to determine the perpetrators involved and the sequence of events on your systems. To start your analysis, you've been given a raw memory dump.

The memory dump file : ransomware_investigation.raw

### Case 2 - Questions

   Based on the memory dump file, answer the following questions:

1. __What suspicious process is running at PID 740?__

2. __What is the full path of the suspicious binary in PID 740?__

3. __What is the parent process of PID 740?__

4. __What is the suspicious parent process PID connected to the decryptor?__

5. __From our current information, what malware is present on the system?__

6. __What DLL is loaded by the decryptor used for socket creation?__

7. __What mutex can be found that is a known indicator of the malware in question?__

8. __What plugin could be used to identify all files loaded from the malware working directory?__

## Case 3 - Crypto John

The on-site forensic investigator has completed the preliminary forensic analysis of John's computer and provided you with the memory dump he created. As the secondary forensic investigator, your task is to extract all necessary information from this memory dump.

The memory dump file: crypto_john.vmem

### Case 3 - Questions

Based on the memory dump file, answer the following questions:

1. __What is John's password?__

## Case 4 - Crypto John

Upon arrival, a photo was taken of the suspect's computer, which showed that John had a command prompt window open. Unfortunately, the picture was not clear enough to discern what actions John was performing in the command prompt.

To enhance your forensic timeline, it would be beneficial to investigate additional details, such as determining the last time John shut down his computer.

The memory dump file: cmd_john.vmem

### Case 4 - Questions

Based on the memory dump file, answer the following questions:

1. __When was the machine last shutdown?__

2. __What did John write?__

## Case 5 - Crypto True

A typical responsibility for forensic investigators involves searching for hidden partitions and encrypted files. Suspicion was heightened after discovering TrueCrypt software and an encrypted partition on the suspect's computer. Although questioning the suspect did not lead to obtaining the passphrase, it's possible that the necessary passphrase could be located within the memory dump taken from the suspect’s computer.

The memory dump file: cryptotrue.vmem

### Case 5 - Questions

Based on the memory dump file, answer the following questions:

- 1. __What is the passphrase of the TrueCrypt Container?__
