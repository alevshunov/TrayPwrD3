# TrayPwrD3
**Keeps dGPU on but idle** until needed. This addresses the Windows 10 stutter/mouse freeze on dual GPU laptops. TrayPwrD3 runs in the background and stays in a tray icon. 

**Other functionality**: single click turns monitor off to save power until you wake it up by moving the mouse or use the keyboard; provides several menu options on right click; more details in Help menu.

This is to address the [Windows 10 and Optimus problem of stutters and mouse hangs](https://forums.geforce.com/default/topic/860554/geforce-mobile-gpus/windows-10-and-optimus/15/). For more about this issue see description on answers.microsoft [Intel + NVIDIA Laptop Freeze Problem](https://answers.microsoft.com/en-us/windows/forum/windows_10-hardware/mobile-gtx-1060-freeze-problem/93e7004a-62b1-4211-8e37-4c136608865e).

**For best results run manually after windows starts** in order to keep resource utilization low. Putting in Windows Autostart folder may casue higher resource utilization.

# Installation
Simply download the [executable](https://github.com/jobeid/TrayPwrD3/tree/master/executable), uncompress it in any folder and run it. 
Notes:
- The executable was compliled for 64bit windows.
- If you don't already have [Visual C++ Redistributable for Visual Studio 2015](https://www.microsoft.com/en-us/download/details.aspx?id=48145) installed, then you could download and install it from Microsoft [here](https://go.microsoft.com/fwlink/?LinkId=746572).
