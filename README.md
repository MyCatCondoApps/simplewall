simplewall [![GitHub stars](https://img.shields.io/github/stars/MyCatCondoApps/simplewall)](https://github.com/MyCatCondoApps/simplewall/stargazers) [![GitHub issues](https://img.shields.io/github/issues/MyCatCondoApps/simplewall)](https://github.com/MyCatCondoApps/simplewall/issues) [![Licence](https://img.shields.io/badge/license-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0.en.html)
=======
#### Definitely for advanced users.
-------

[![simplewall](https://www.henrypp.org/images/simplewall.png?gd)](https://github.com/henrypp/simplewall/issues/250)

### Description:
This is a simple tool to configure the Windows Filtering Platform (WFP), which can configure the network activity on your computer.

The lightweight application is less than a megabyte, and it is compatible with Windows Vista and higher operating systems.
You can download either the installer or the portable version. For it to work correctly, it needs administrator privilages.

### Command line:
List of arguments for `simplewall.exe`:
- `/install` - enable filtering (you can set `/silent` argument to skip prompt)
- `/uninstall` - remove all installed filters

### Uninstall:
When you uninstall simplewall, all previously installed filters will stay alive in your system.
To remove all filters created by simplewall, simply start simplewall and press "Disable filters" button.


```
To activate portable mode, create "simplewall.ini" in application folder, or move it from "%APPDATA%\Henry++\simplewall".
```

### FAQ:
- Is it safe to use simplewall with Windows Firewall? Yes.
- How can I disable blocklist entirely? Click "Disable filters" when simplewall starts up.
- [How to remove Windows Security center warnings](https://www.howtogeek.com/244539/how-to-disable-the-action-center-in-windows-10/) [win10 1607+](https://serverfault.com/a/880672)
- [Windows Security center integration (impossible)](https://stackoverflow.com/questions/3698285/how-can-i-tell-the-windows-security-center-that-im-an-antivirus/3698375#3698375)

Website: [mycatcondo.ga](https://mycatcondo.ga)<br />
Support: realmycatcondo@gmail.com<br />
<br />
Free for personal use and commercial use. Made by [Henry++](https://github.com/henrypp). Forked by [MyCatCondo Apps](https://github.com/MyCatCondoApps/).
