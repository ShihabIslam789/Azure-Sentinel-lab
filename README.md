# Azure-Sentinel-lab

This project used Microsoft Azure which is an online computing platform that offers analytic tools which allows Users to protect themselves from the Internet of Things. This tool can be used for Security information and event management (SIEM) for all logins. 

## How It Works

The software allows me to create a virtual machine that mimics a clean installation of any Operating System and record user access. When I turn off the innate Firewall and put this vunerable system to the public I can record which bad actor tries to connect to my account. Malicious actors try to brute force into my Virtual machine by guessing the username and password. 

 ![Windows](https://github.com/ShihabIslam789/Azure-Sentinel-lab/blob/main/PIctures/Terminal%20picture.png)

 The malicious actors attempts are recorded to plaintext on the computer and this information contains their IP address and example Username and password. we can find this because I am using the geolocation API to pull this information, but an account is needed first.

 Link:(https://ipgeolocation.io/)

 ### Goal

 My goal was to take this information and make it readable by someone who doesn't work in my field. So I made a map of where the attacks come from based on the Log file I obtained and collected.
 The colored map show attacks with a legend telling how many. This is the goal of Azure is to analysis potential threats and dealing with them before it becomes  a problem.

 ![Windows2](https://github.com/ShihabIslam789/Azure-Sentinel-lab/blob/main/PIctures/Attempted_Logins.png)


#### How To Be Better Protected(NIST framework)

Going forward into the future all Computer users want to protect themselves from any attack possible. If external people get into the system then all the files are in jeopardy. Any user should protect themselves by making complex username and passwords for their account. the more complex it is for any to guess your credentials. Also double check that your firewall is on so it can detect any problems and will alert you if there is. Once someone gets into your account recovery maybe difficult. A factory default option maybe the only way to save the computer.     
