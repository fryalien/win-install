**Legacy Right Click Context Menu**

>Open `Windows Terminal` and run this command:

```
reg.exe add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f /ve
```

>Restart File Explorer.


**To undo this change, in a `Windows Terminal`, run this command:**

```
reg.exe delete "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}" /f
```

>Restart the File Explorer or Computer for the changes to take effect.