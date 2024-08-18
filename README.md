# Remote-Desktop-Time-limit

To Configure it please proceed with the following steps:


- Click Windows Start in the Server and type gpedit.msc,
- In the left panel, navigate to:

Computer Configuration > Administrative Templates > Windows Components > Remote Desktop Services > Remote Desktop Session Host > Session Time Limits.

- In the right panel, double-click the Set time limit for active but idle Remote Desktop Services sessions policy: in the modal window that will appear, activate it by switching the radio button from Not configured to Enabled, then set the desired amount of time in the drop-down list right below.

- Apply and you are set to go.
