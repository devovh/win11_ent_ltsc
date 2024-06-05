# Windows 11 IoT Enterprise LTSC

* 1.Code->Download Zip
* 2.Unpack
* 3.Install/Run

* Activate to Full Version:
```bash
* Open Convert_to_Windows_10_LTSC and run as Administrator - loader.bat
* Open CMD as Administrator and paste/run commands:
* slmgr /upk
* slmgr /ipk M7XTQ-FN8P6-TTKYV-9D4CC-J462D
* slmgr /skms kms.ddns.net
* slmgr /ato
* Finaly You have a Full version Windows 11 Enterprise LTSC
```
* Windows Store:
```bash
* Open CMD as Administrator and paste/run command:
* wsreset -i
* Wait installation and done You have a Windows Store
```
* Windows Security Center / Windows Defender / UI:
```bash
* Run Hide_Account_protection_in_Windows_Defender_Security_Center.reg
* Open Powershell as Administrator and paste/run command:
* Set-ExecutionPolicy Unrestricted - Y
* Change the folder in powershell to the one downloaded from this link:
* e.g. cd C:\Users\username\Desktop\win11_ent_ltsc
* Run command:
* Add-AppxPackage -Path "C:\Users\username\win11_ent_ltsc\Microsoft.UI.Xaml.2.7_7.2208.15002.0_x64__8wekyb3d8bbwe.Appx"
* and
* Add-AppxPackage -Path "C:\Users\username\win11_ent_ltsc\Microsoft.SecHealthUI_8wekyb3d8bbwe.appx"
* Restart Computer.
* In the username field, enter your username. Of course, it is best to use a local Windows account, not an online one.
* Enjoy window UI for windows defender on this system.
```