# gpdroid 
Guidelines for Android Pen Testing. This collection includes tools for Static analysis, Dynamic Analysis, Network Traffic Analyzer, and Anti-viruses as well as checklists for security assessment.

# Static Analysis
## Mobsf
We recommend to utilize this tool.

#### Capabilities
* A complete assessment of application security

#### Operational Environments
* It is based on Python (Django framework).

#### Whereis
* Download from [Mobile-Security-Framework-MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF.git)

#### Advantages
* Open source
* Do not require root access
* It provides a user-friendly report


#### Limitations

# Dynamic Analysis
## Drozer
Dynamic security assessment for Android.
#### Capabilities
* Check vulnerability in components
* Create exploit for existing vulnerability

#### Operational Environments
* It comes with an agent app you need to install it on the mobile and so, the drozer interacts with it using adb.

#### Whereis
* Download from [drozer](https://github.com/FSecureLABS/drozer.git)

#### Advantages
* Open source
* Does not require root access


# Network Traffic Analyzer
## Netmonitor

#### Capabilities
* Sniff (monitor) connections established by device

#### Operational Environments
* Installed on Android OS

#### Whereis
* Download from [F-Droid](https://f-droid.org/en/packages/org.secuso.privacyfriendlynetmonitor/)

#### Advantages
* Open source
* Do not require root access
* Easy launching
* Display trafic per app: so, you can check your desire app's traffic
* Display all traffic outgoing your device
  * either browser, applications, websocket, and so forth
* Shallow learning curve  

#### Limitations
- Unable to decrypt the SSL traffic

# Anti-viruses

# Emulators
Genymotion

BlueStacks Android emulator

Android Studio's emulator 


# Security assessment checklists
Mobile Security Testing Guide (MSTG). Github [page](https://github.com/OWASP/owasp-mstg)
