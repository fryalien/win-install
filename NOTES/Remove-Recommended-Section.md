**Remove recommended section from Windows 11**

>Open the `Group Policy Editor` window.

Expand:

	- Computer Configuration
	- Administrative Templates
	- select Start Menu and Taskbar

`Double-click` on the `Remove Recommended` section from Start Menu setting.

This will open a new window.

Select the `Enabled` option in that window.

Press the `Apply` button and then the OK button.

>If you want to show the Recommended section in the Start menu

follow upper steps and select the `Not Configured` option for the same Group Policy setting.

Use Apply button and OK button to save the setting.

---

>From the registry:

HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\Explorer

There will be a `HideRecommendedSection DWORD` value that is used for the Recommended section of the Start menu.

TO hide recommended section set the `REG-DWORD` value to `1`. 