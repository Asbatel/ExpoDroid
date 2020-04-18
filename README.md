# Welcome to ExpoDroid
Hook-based Android Malware Scanner based on Xposed framework <img src="https://github.com/Asbatel/ExpoDroid/blob/master/app/src/main/res/mipmap-mdpi/ic_launcher.png" width="80" align="right">

# Requirements

ExpoDroid uses the following tools:

   - **Xposed framework**: It provides the ability to change some operating system related elements as well as applications that we want to test without counting on the source code. Precisely, It permits the hooking of methods and the addition of any desired changes. (https://www.xda-developers.com/xposed-framework-hub/)
   
   - **VirusTotal API**: It lets you upload and scan apks for malware. (https://developers.virustotal.com/reference)

# Installation

   1- Download or clone the repo (git clone https://github.com/Asbatel/ExpoDroid.git)
   2- Install the Xposed Framework 
   3- Sign up to VirusTotal Community to obtain the **API Key**.
  
# How the Scanner works?

 1- Hooking and stoping the package installer from installing the target app.
 2- Calculating the hash and using VirusTotal API to analyze it for malware
 3- Display the results in details to the user (in case of a malware)
 
 <img src="https://github.com/Asbatel/ExpoDroid/blob/master/Screenshots/malwarescore.jpg" width="140" align="left">
 <img src="https://github.com/Asbatel/ExpoDroid/blob/master/Screenshots/malwarestats.jpg" width="140" align="middle">
 <img src="https://github.com/Asbatel/ExpoDroid/blob/master/Screenshots/malwarefamily.jpg" width="140" align="right">

