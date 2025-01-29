**ENABLE NOTIFICATIONS**

`Computer\HKEY_CURRENT_USER\SOFTWARE\Policies\Microsoft\Windows\Explorer`

`DisableNotificationCenter` value is set to `0`

```
reg.exe add "HKEY_CURRENT_USER\Software\Policies\Microsoft\Windows\Explorer" /v DisableNotificationCenter /t REG_DWORD /d 1 /f
```
