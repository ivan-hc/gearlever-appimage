# gearlever-appimage
Unofficial. An utility to organize and manage AppImage files for you, generate desktop entries and app metadata, update apps in-place or keep multiple versions side-by-side.

------------------------------------------------------------------------

### NOTE: This wrapper is not verified by, affiliated with, or supported by [mijorus](https://github.com/mijorus/gearlever).

**The base software is only distributed [on FlatHub](https://flathub.org/apps/details/it.mijorus.gearlever) as a Flatpak app, but being unofficially available on the [Arch User Repository](https://aur.archlinux.org/packages/gearlever) (AUR), I repackaged it as an AppImage for demonstration purposes, for the original authors, to promote this packaging format to them. Consider this package as "experimental". I also invite you to request the authors to release an official AppImage, and if they agree, you can show this repository as a proof of concept.**

------------------------------------------------------------------------

## Known issue

This prototype is an "[Archimage](https://github.com/ivan-hc/ArchImage)", i.e., an Arch Linux **container** inside an AppImage that alternately uses its own BubbleWrap and PROOT to mount a few directories on the host system for integration, and **only uses the libraries it has inside**.

For this reason:
1. **traditional AppImages** (**not Archimages**) can be launched without problems, but **only if they don't require libraries from the host system**, that is, outside of those contained in GearLever AppImage (being a portable container, it acts as a "host system" for other AppImages)
2. **other ArchImages**, however, cannot be launched at all (error message says **Nested JuNest environments are not allowed** in BubbleWrap/normal mode, a **Fusermount** related error instead shows up in PROOT mode)

Anywaym, it is possible to use this AppImage for all other GearLever features (menu integration, updates, etc...) for both classic AppImages and Archimages.

If you want learn more about Archimages, visit https://github.com/ivan-hc/ArchImage

------------------------------------------------------------------------

## Alternative native build

In "AM" package manager you can install and manage the native build maintained by [@fiftydinar](https://github.com/fiftydinar)

https://github.com/pkgforge-dev/Gear-Lever-AppImage

------------------------------------------------------------------------

## Install and update it with ease

### *"*AM*" Application Manager* 
#### *Package manager, database & solutions for all AppImages and portable apps for GNU/Linux!*

[![sample.png](https://raw.githubusercontent.com/ivan-hc/AM/main/sample/sample.png)](https://github.com/ivan-hc/AM)

[![Readme](https://img.shields.io/github/stars/ivan-hc/AM?label=%E2%AD%90&style=for-the-badge)](https://github.com/ivan-hc/AM/stargazers) [![Readme](https://img.shields.io/github/license/ivan-hc/AM?label=&style=for-the-badge)](https://github.com/ivan-hc/AM/blob/main/LICENSE)

*"AM"/"AppMan" is a set of scripts and modules for installing, updating, and managing AppImage packages and other portable formats, in the same way that APT manages DEBs packages, DNF the RPMs, and so on... using a large database of Shell scripts inspired by the Arch User Repository, each dedicated to an app or set of applications.*

*The engine of "AM"/"AppMan" is the "APP-MANAGER" script which, depending on how you install or rename it, allows you to install apps system-wide (for a single system administrator) or locally (for each user).*

*"AM"/"AppMan" aims to be the default package manager for all AppImage packages, giving them a home to stay.*

*You can consult the entire **list of managed apps** at [**portable-linux-apps.github.io/apps**](https://portable-linux-apps.github.io/apps).*

## *Go to *https://github.com/ivan-hc/AM* for more!*

------------------------------------------------------------------------

| [***Install "AM"***](https://github.com/ivan-hc/AM) | [***See all available apps***](https://portable-linux-apps.github.io) | [***Support me on ko-fi.com***](https://ko-fi.com/IvanAlexHC) | [***Support me on PayPal.me***](https://paypal.me/IvanAlexHC) |
| - | - | - | - |

------------------------------------------------------------------------
