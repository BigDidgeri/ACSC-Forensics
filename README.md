# ACSC-Forensics #

## Section 1 - Getting Started ##
### GS-1 - How many hosts have we recieved data from? ###
```9```

### GS-2 - What is the MD5 hash of the memory image provided? Flag format: MD5 hash ###
```20b25f76cc1839c2e7759a69a82bf664```

### GS-3 - What time was this image taken? (If using Volatility 2. Use profile Win10x64_17134) Flag Format: yyyy-mm-dd hh:mm:ss ###
```2021-04-06 01:56:57```

![image](https://user-images.githubusercontent.com/18509521/213969553-4730d193-7a74-4f5e-8351-e3d925ddf95f.png)


### GS-4 - What website management platform are ALIEN using for their public facing website? Flag format: FullNameOfPlatform ###

## Section 2 - Initial Access ##
### IA-1 - The actor seems to have initially failed to install themselves on the web server. What IP address did their malicious wizardry come from? Flag format: IPv4 ###

### IA-2 - It looks like the actor eventually succeeded in gaining access using a combination of multiple well-documented CVEs. Which of these is the most recent? Flag format: cve-1-1 ###

### IA-3 - What was the filename of the first file created by the actor to test that their exploit worked? (We'll refer to this test file as sample 1) Flag format - filename.ext ###

### IA-4 - After calling home, the actor finally succeeded in dropping their core tool, sample 2.What time (UTC) was this tool first used? Flag format: yyyy-mm-dd hh:mm:ss ###
