### **VirtualBox Installation:**

- https://www.virtualbox.org/wiki/Downloads
- Install VirtualBox on Mac: https://cs.hofstra.edu/docs/pages/guides/vbox_mac.html
- Install VirtualBox on Linux: https://phoenixnap.com/kb/install-virtualbox-on-ubuntu
- Install VirtualBox on Windows: [https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170)

**Windows Installation:**

• https://www.microsoft.com/en-us/evalcenter/download-windows-10-enterprise

**Windows Configuration:**

Disable Windows Defender

### **Commands**

### **Disable real-time protection**

`Set-MpPreference -DisableRealtimeMonitoring $true`

### **Disable the scanning of network files**

`Set-MpPreference -DisableScanningNetworkFiles $true`

### **Disable the blocking of files at first sight**

`Set-MpPreference -DisableBlockAtFirstSeen $true`

### **Disable Windows Defender AntiSpyware**

`reg add "HKLM\SOFTWARE\Policies\Microsoft\Windows Defender" /v DisableAntiSpyware /t REG_DWORD /d 1 /f`

**Ubuntu Installation:**

• Ubuntu desktop download: https://ubuntu.com/download/desktop

Ubuntu Configuration:

### **Commands**

### **Update system packages**

`sudo apt update`

### **Install required packages**

`sudo apt install bzip2 tar gcc make perl git`

### **Install the generic kernel headers**

`sudo apt install linux-headers-generic`

### **Install our system-specific kernel headers**

`sudo apt install linux-headers-$(uname -r)`

### **Course Repo:**

[https://github.com/MalwareCube/SOC101](https://github.com/MalwareCube/SOC101.git)
