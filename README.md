# blondy-virtual-desktop
Sets virtual Desktop Background in Windows 10 on desktop change

This is the code from [this project](https://www.codeproject.com/Tips/1030472/Setting-The-Virtual-Desktop-Background-In-Windows?fid=1891480&df=90&mpp=25&sort=Position&spc=Tight&prof=True&view=Expanded&fr=1#xx0xx) on [CodeProject.com](https://www.codeproject.com) 

Full attribution should go to this and to [Blondy314](https://www.codeproject.com/Members/Blondy314).

I have also implemented the changed recommended by [Member 11131576](https://www.codeproject.com/script/Membership/View.aspx?mid=11131576) to update the GUID Attribute from "AF8DA486-95BB-4460-B3B7-6E7A6B2962B5" to "f31574d6-b682-4cdc-bd56-1827860abec6"

This also fixes the crashes that occur when running the application.

## Using
Feel free to download the solution and recompile, or download the VirtualDesktop.exe file from [/bin/Debug](/celtboy/blondy-virtual-desktop/tree/main/bin/Debug)

### Known Bugs

- You have to right-click on the System Tray Icon and select 'Show' twice in order to see the window.
- Setting of wallpapers have a definite delay upon switching as this is tick-based.

This code was originally licensed under the [CPOL](https://www.codeproject.com/info/cpol10.aspx) but that is not available as a valid license type in GitHub. Please use it appropriately.
