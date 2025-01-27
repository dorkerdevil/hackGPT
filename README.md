![](https://img.shields.io/badge/PwnAI-v23-brightgreen)

<img width="1568" alt="hackGPT" src="https://user-images.githubusercontent.com/3261849/208184172-b5d79eb2-3dff-49e7-b735-d991c08e6ec8.png">
<p align="center">
  
`Automate the parsing and analysis of json threat data from CyberDefense tools like my SecurityScorecard ASI API tool here: https://github.com/securityscorecard/ssc-asi-tools/tree/master/tools/SSC_APIHunter:`
  
<img width="1683" alt="sscplushgpt" src="https://user-images.githubusercontent.com/3261849/217700643-ab202279-9558-41da-83db-ce64f7e796a1.png">


`Automate CVE exploit creation and CyberDefense protections:` (results https://github.com/NoDataFound/PwnAI/tree/main/output)

<img width="1649" alt="Screenshot 2022-12-14 at 8 08 05 AM" src="https://user-images.githubusercontent.com/3261849/207626394-cb272c96-c370-4870-9a13-6d43397fb830.png">

`Ask ChatGPT to print its own source`

<img width="675"  alt="Screenshot 2022-12-16 at 4 46 35 PM" src="https://user-images.githubusercontent.com/3261849/208202201-db534197-71c8-4f26-8041-72dd25e8d356.png">


<img width="977" alt="Screenshot 2022-12-04 at 6 27 59 PM" src="https://user-images.githubusercontent.com/3261849/205525745-fa26c95b-9d86-4c84-8669-be1cde4abaf2.png">

<img width="1269" alt="Screenshot 2022-12-04 at 6 32 40 PM" src="https://user-images.githubusercontent.com/3261849/205525669-9eb6e988-4440-43ea-8432-6f07066db7df.png">

https://user-images.githubusercontent.com/3261849/206036893-b583fad1-6b77-4dfb-8424-639229ffdd19.mov

<img align="center" width="1800" alt="hackGPT" src="https://user-images.githubusercontent.com/3261849/211083766-e987961a-4f0a-427c-bbd8-6479f4449342.png"></p>

## 𝗜𝗻𝘀𝘁𝗮𝗹𝗹𝗮𝘁𝗶𝗼𝗻
`Clone this repo`
```
git clone https://github.com/NoDataFound/PwnAI.git
```
`Install dependancies`
```
python3 -m pip install -r requirements.txt
```
`Review Input and Bulk Input samples`
```
head -n 10 input/malware/malware_sample && head -n 10 input/sample_sources

# Exploit Title: TP-Link Tapo c200 1.1.15 - Remote Code Execution (RCE)
# Date: 02/11/2022
# Exploit Author: hacefresko
# Vendor Homepage: https://www.tp-link.com/en/home-networking/cloud-camera/tapo-c200/
# Version: 1.1.15 and below
# Tested on: 1.1.11, 1.1.14 and 1.1.15
# CVE : CVE-2021-4045

# Write up of the vulnerability: https://www.hacefresko.com/posts/tp-link-tapo-c200-unauthenticated-rce

https://github.com/rapid7/metasploit-payloads/blob/master/python/meterpreter/meterpreter.py
https://github.com/rapid7/metasploit-payloads/blob/master/powershell/MSF.Powershell/Meterpreter/Core.cs
```

`Open Jupyter Notebook`
*Install Juypter Notebook if needed - use pip or download binaries here: https://jupyter.org/*
```
pip3 install jupyter notebook
```
`install (pictured) https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter-renderers`


## 𝖫𝖺𝗎𝗇𝖼𝗁 𝖭𝗈𝗍𝖾𝖻𝗈𝗈𝗄 𝘄𝗶𝘁𝗵 𝗩𝗦𝗰𝗼𝗱𝗲

<p align="center">
<img align="center" src="https://user-images.githubusercontent.com/3261849/205510169-5269cde5-7565-4094-9a07-2d41e65bc717.png"></p> 

`Configure .env with your OpenAI API key(notebook will help you)`

## Use Python 
`set API key on launch`
<img width="959" alt="Screenshot 2022-12-03 at 1 23 38 PM" src="https://user-images.githubusercontent.com/3261849/205458244-ed556dd8-c8d8-498d-9a1d-727d139e46d7.png">

`single searches`
```
python3 PwnAI.py
```
<img width="1147" alt="Screenshot 2022-12-04 at 6 26 38 PM" src="https://user-images.githubusercontent.com/3261849/205525796-d8d009b5-9d76-4b04-ae24-319e5f1ea924.png">


`Bulk searches`
```
python3 PwnAI_bulk.py
```
<img width="977" alt="Screenshot 2022-12-04 at 6 27 59 PM" src="https://user-images.githubusercontent.com/3261849/205525811-8c5eb58b-257e-4412-a462-89f0c3ccb5be.png">

