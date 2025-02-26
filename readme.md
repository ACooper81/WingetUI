# WingetUI: A package manager UI

[![Downloads@latest](https://img.shields.io/github/downloads/martinet101/WingetUI/total?style=for-the-badge)](https://github.com/martinet101/WingetUI/releases/latest/download/WingetUI.Installer.exe)
[![Release Version Badge](https://img.shields.io/github/v/release/martinet101/WingetUI?style=for-the-badge)](https://github.com/martinet101/WingetUI/releases)
[![Issues Badge](https://img.shields.io/github/issues/martinet101/WingetUI?style=for-the-badge)](https://github.com/martinet101/WingetUI/issues)
[![Closed Issues Badge](https://img.shields.io/github/issues-closed/martinet101/WingetUI?color=%238256d0&style=for-the-badge)](https://github.com/martinet101/WingetUI/issues?q=is%3Aissue+is%3Aclosed)

<br>The main goal of this project is to create an intuitive GUI for the most common CLI package managers for Windows 10 and Windows 11, such as [Winget](https://learn.microsoft.com/en-us/windows/package-manager/) and [Scoop](https://scoop.sh/).  

With this app, you'll be able to easily download, install, update and uninstall any software that's published on the supported package managers — and so much more.

<br>**Disclaimer:** This project has no connection with the official [Winget project](https://github.com/microsoft/winget-cli) — it's completely unofficial. 

Beware that neither Microsoft nor the creators of WingetUI are responsible for the downloaded apps. 

[![Status](https://img.shields.io/badge/Project%20current%20development%20status-Active-brightgreen?style=for-the-badge)]()

![image](https://raw.githubusercontent.com/martinet101/WingetUI/main/media/main.webp)

# Features

 - The ability to install packages from Scoop and Winget (the idea is to add more package managers in the future).
 - The ability to upgrade and uninstall previously installed packages — as well as uninstall local PC apps!
 - The ability to both import and export the packages of your choice, so that you can easily install them in the future.
 - The user doesn't need to install any of the package managers. (Although the app does include the ability to install Scoop for you!)
 - Includes support for managing Scoop buckets.
 - The user can select the version that they want to install of any particular app.
 - The user will be notified whether the installation/update/uninstallation of an app was completed successfully or not.
 - The ability to queue installations in order to prevent conflicts.
 - A dark theme is available to prevent you from burning your eyes. :sunglasses:
 - The ability to show package-related information (like its license, SHA256 hash, homepage, etc.) before installation.
 - More than 6800 packages available and counting!
 - More features are coming in the future!

# Consider supporting me. 

**It really does make a big difference, and is very much appreciated.**

<a href='https://ko-fi.com/martinet101' target='_blank'><img style='border:0px;height:36px;' src='https://az743702.vo.msecnd.net/cdn/kofi3.png?v=0' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>

Thank you! :)

# Installation

<p>There are multiple ways to install WingetUI — choose whichever one you prefer!<br><br></p>

- The first is by downloading the latest version of the installer:
<br>

<p align="center"><b><a href="https://github.com/martinet101/WingetUI/releases/latest/download/WingetUI.Installer.exe">Click here to download WingetUI</a></b></p>
<br>

- The second is by using [Winget](https://learn.microsoft.com/en-us/windows/package-manager/):

Run the following command in PowerShell or Command Prompt: `winget install wingetui`

<br>

- The third is by using [Scoop](https://scoop.sh/) — see the instructions below.

In case it's not already added, it's required to add the _Extras_ bucket first: `scoop bucket add extras`

Then, to install WingetUI, execute the following command: `scoop install wingetui`

<br><p align="center"><i>Check out the <a href="https://github.com/martinet101/WingetUI/wiki">Wiki</a> for more information!</i></p>


## Translating WingetUI to other languages
In order to translate WingetUI to other languages or to update an old translation, please see [Translating WingetUI - WingetUI Wiki](https://github.com/martinet101/WingetUI/wiki#translating-wingetui) for more info.


### Currently Supported languages
<!-- Autogenerated translations -->
| Language | Translated | |
| :-- | :-- | --- |
| Catalan - Català | 100% | <img src='https://flagcdn.com/ad.svg' width=20> |
| German - Deutsch | 100% | <img src='https://flagcdn.com/de.svg' width=20> |
| English - English | 100% | <img src='https://flagcdn.com/gb.svg' width=20> |
| French - Français | 100% | <img src='https://flagcdn.com/fr.svg' width=20> |
| Hindi - हिंदी | 95% | <img src='https://flagcdn.com/in.svg' width=20> |
| Hungarian - Magyar | 100% | <img src='https://flagcdn.com/hu.svg' width=20> |
| Japanese - 日本語 | 100% | <img src='https://flagcdn.com/jp.svg' width=20> |
| Russian - Русский | 95% | <img src='https://flagcdn.com/ru.svg' width=20> |
| Serbian - Srpski | 24% | <img src='https://flagcdn.com/rs.svg' width=20> |
| Italian - Italiano | 100% | <img src='https://flagcdn.com/it.svg' width=20> |
| Portuguese (Brazil) | 100% | <img src='https://flagcdn.com/br.svg' width=20> |
| Portuguese (Portugal) | 100% | <img src='https://flagcdn.com/pt.svg' width=20> |
| Turkish - Türkçe | 95% | <img src='https://flagcdn.com/tr.svg' width=20> |
| Ukranian - Yкраї́нська | 95% | <img src='https://flagcdn.com/ua.svg' width=20> |
| Simplified Chinese (China) | 100% | <img src='https://flagcdn.com/cn.svg' width=20> |
| Traditional Chinese (Taiwan) | 100% | <img src='https://flagcdn.com/tw.svg' width=20> |

Last updated: Thu Dec  8 00:57:50 2022
<!-- END Autogenerated translations -->


## Contributions
 WingetUI wouldn't have been possible without the help of our dear contributors. From the person who fixed a typo to the person who improved half of the code, WingetUI wouldn't be possible without them! :smile:<br><br>

### Contributors:
 [![My dear contributors](https://contrib.rocks/image?repo=martinet101/WingetUI)](https://github.com/martinet101/WingetUI/graphs/contributors)<br><br>
 
 ### Translators:
 WingetUI has not been machine translated! The following users have been in charge of the translations:
- Aaron liu: Chinese
- Ahmet Özmetin: Turkish
- Artem Moldovanenko: Ukranian
- BUGP Association: Chinese
- Cololi: Chinese
- Datacra5H: German
- Evans: French
- GiacoBot: Italian
- Gidano: Hungarian
- Maicol Battistini: Italian
- Nemanja Djurcic: Serbian, Croatian
- Operator404: Ukranian
- ppvnf: Portuguese (Portugal and Brazil)
- Rosario Di Mauro: Italian
- Satyam Singh Niranjan: Hindi
- Sergey: Russian
- sho9029: Japanese
- TAKASE, Yuki: Japanese
- yrctw: Chinese
- Артем Скляров: Russian
- Martí Climent: Catalan
 

# Screenshots
 
![image](https://raw.githubusercontent.com/martinet101/WingetUI/main/media/winget_1.png)

![image](https://raw.githubusercontent.com/martinet101/WingetUI/main/media/winget_2.png)

![image](https://raw.githubusercontent.com/martinet101/WingetUI/main/media/winget_3.png)

![image](https://raw.githubusercontent.com/martinet101/WingetUI/main/media/winget_4.png)

![image](https://raw.githubusercontent.com/martinet101/WingetUI/main/media/winget_5.png)

![image](https://raw.githubusercontent.com/martinet101/WingetUI/main/media/winget_6.png)

![image](https://raw.githubusercontent.com/martinet101/WingetUI/main/media/winget_7.png)

![image](https://raw.githubusercontent.com/martinet101/WingetUI/main/media/winget_8.png)


# FAQ

**Q: I am unable to install or upgrade a specific Winget package! What should I do?**<br>

A: This is likely an issue with Winget rather than WingetUI. 

Please check if it's possible to install/upgrade the package through PowerShell or the Command Prompt by using the commands `winget upgrade` or `winget install`, depending on the situation (for example: `winget upgrade --id Microsoft.PowerToys`). 

If this doesn't work, consider asking for help at [Winget's own project page](https://github.com/microsoft/winget-cli).<br>

#

**Q: The name of a package is trimmed with ellipsis — how do I see its full name/id?**<br>

A: This is a known limitation of Winget. 

See more details in issue https://github.com/microsoft/winget-cli/issues/2603.<br>

#

**Q: My antivirus is telling me that WingetUI is a virus! / My browser is blocking the download of WingetUI!**<br>

A: A common reason apps (i.e., executables) get blocked and/or detected as a virus — even when there's nothing malicious about them, like in the case of WingetUI — is because they're not being used by a relatively large amount of people.

Combine that with the fact that you might be downloading something that was recently released, and simply blocking unknown apps is in many cases a good precaution to take in order to prevent actual malware.

Since WingetUI is open source and safe to use, simply whitelist the app in the settings of your antivirus/browser.<br>

#

**Q: Will Chocolatey be supported?**<br>

A: This is currently under study. 

See more details in issue https://github.com/martinet101/WingetUI/issues/56.<br>

#

**Q: Can I add "msstore" as a source for Winget in the app?**<br>

A: This is not possible, nor is it planned for the near future. 

See more details in issue https://github.com/martinet101/WingetUI/issues/87.<br>

#

**Q: Are Winget/Scoop packages safe?**<br>

A: WingetUI, Microsoft and Scoop aren't responsible for the packages available for download, which are provided by third parties and can theoretically be compromised.

To mitigate the risks of downloading malware, Microsoft has implemented a few checks for the software available on Winget. Even so, It's recommended to only download software from publishers that you trust. 

<br><p align="center"><i>Check out the <a href="https://github.com/martinet101/WingetUI/wiki">Wiki</a> for more information!</i></p>
