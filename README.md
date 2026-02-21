#### ⚠️ Do not download APKs or modules from random websites you find on Google, as they may be dangerous and because providers impersonate ReVanced/ReVanced Extended/Morphe. Please build your application from official sources or use open source builders like this one.

# ReVanced x Morphe Builder

[![CI](https://github.com/dj-tanjid/Morphe-ReVancedX-Builder/actions/workflows/ci.yml/badge.svg?event=schedule)](https://github.com/dj-tanjid/Morphe-ReVancedX-Builder/actions/workflows/ci.yml)
[![GitHub License](https://img.shields.io/github/license/dj-tanjid/Morphe-ReVancedX-Builder?logo=gnu&label=License&link=https%3A%2F%2Fgithub.com%2Fdj-tanjid%2FMorphe-ReVancedX-Builder%2Fblob%2Fmain%2FLICENSE)](https://github.com/dj-tanjid/Morphe-ReVancedX-Builder/blob/main/LICENSE)
[![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/dj-tanjid/Morphe-ReVancedX-Builder/total?logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjI0IiBoZWlnaHQ9IjI0Ij48cGF0aCBkPSJNNC43NSAxNy4yNWEuNzUuNzUgMCAwIDEgLjc1Ljc1djIuMjVjMCAuMTM4LjExMi4yNS4yNS4yNWgxMi41YS4yNS4yNSAwIDAgMCAuMjUtLjI1VjE4YS43NS43NSAwIDAgMSAxLjUgMHYyLjI1QTEuNzUgMS43NSAwIDAgMSAxOC4yNSAyMkg1Ljc1QTEuNzUgMS43NSAwIDAgMSA0IDIwLjI1VjE4YS43NS43NSAwIDAgMSAuNzUtLjc1WiIgZmlsbD0iI0ZGRkZGRiI+PC9wYXRoPjxwYXRoIGQ9Ik01LjIyIDkuOTdhLjc0OS43NDkgMCAwIDEgMS4wNiAwbDQuOTcgNC45NjlWMi43NWEuNzUuNzUgMCAwIDEgMS41IDB2MTIuMTg5bDQuOTctNC45NjlhLjc0OS43NDkgMCAxIDEgMS4wNiAxLjA2bC02LjI1IDYuMjVhLjc0OS43NDkgMCAwIDEtMS4wNiAwbC02LjI1LTYuMjVhLjc0OS43NDkgMCAwIDEgMC0xLjA2WiIgZmlsbD0iI0ZGRkZGRiI+PC9wYXRoPjwvc3ZnPg==&label=Downloads&link=https%3A%2F%2Fgithub.com%2Fdj-tanjid%2FMorphe-ReVancedX-Builder%2Freleases)](../../releases)

A fork of [ReVanced Builder](https://github.com/j-hc/revanced-magisk-module) by j-hc

This ReVanced/Morphe builder creates both APKs and [Magisk](https://github.com/topjohnwu/Magisk)/[KernelSU](https://github.com/tiann/KernelSU) modules for [ReVanced](https://github.com/ReVanced), [ReVanced Extended by Anddea](https://github.com/anddea/revanced-patches), and [Morphe](https://github.com/MorpheApp) versions of **YouTube**, **YouTube Music**, **Google Photos** & **Reddit**.

<details><summary><big>Features</big></summary>
<ul>
 <li> Supports all present and future ReVanced & Morphe apps (including projects implementing the same API)</li>
 <li> Can build root Modules and non-root APKs</li>
 <li> Updated daily with the latest versions of apps and patches</li>
 <li> Optimizes APKs and modules for size</li>
 <li> Modules</li>
    <ul>
     <li> recompile invalidated odex for faster usage</li>
     <li> receive updates from Magisk/KSU app</li>
     <li> do not break safetynet or trigger root detections</li>
     <li> handle installation of the correct version of the stock app and all that</li>
     <li> support Magisk and KernelSU</li>
    </ul>
</ul>
</details>

#### **Get the [**Latest Release**](../../releases/latest)!**

## Installation
### Non-root users
- Install the [ReVanced GmsCore app](https://github.com/ReVanced/GmsCore/releases/latest) or the [Morphe MicroG-RE app](https://github.com/MorpheApp/MicroG-RE/releases/latest).
- Download the APK files you want to install from the [releases page](../../releases/latest).
- (Optional) Import one of my [**Custom Settings**](../teejay/custom_settings-by_tanjid) into your application. [*How to do this?*](https://github.com/dj-tanjid/Morphe-ReVancedX-Builder/teejay/?tab=readme-ov-file#import-custom-settings-in-revancedmorphe-applications)
- Enjoy!

### Root users
- Download the ZIP files you want to flash from the [releases page](../../releases/latest).
- (Optional) Import one of my [**Custom Settings**](../teejay/custom_settings-by_tanjid) into your application. [*How to do this?*](https://github.com/dj-tanjid/Morphe-ReVancedX-Builder/teejay/?tab=readme-ov-file#import-custom-settings-in-revancedmorphe-applications)
- (Optional) Use [**zygisk-detach**](https://github.com/j-hc/zygisk-detach) to detach YouTube and YT Music from Play Store if you are using magisk modules.
- Enjoy!

## Import custom settings in ReVanced/Morphe applications
I personally like my YouTube and YouTube Music applications to be as close as possible to the original look, but less cluttered, easier, and less annoying to use. If you feel the same, I highly recommend importing [my custom settings files](../teejay/custom_settings-by_tanjid).

**To do this, go to YouTube Settings &rarr; ReVanced/ReVanced Extended/Morphe &rarr; Miscellaneous &rarr; Import&nbsp;/&nbsp;Export settings.**

## To include/exclude patches or patch other apps

 * Star the repo :eyes:
 * Use the repo as a [template](https://github.com/new?template_name=revanced-magisk-module&template_owner=j-hc)
 * Customize [`config.toml`](./config.toml) using [rvmm-config-gen](https://j-hc.github.io/rvmm-config-gen/)
 * Run the build [workflow](../../actions/workflows/build.yml)
 * Grab your modules and APKs from [releases](../../releases)

also see here [`CONFIG.md`](./CONFIG.md)

## If you are having trouble with the classic mount method of the modules
such as,
- **"Reflash needed"** error after reboots
- **"Suspicious mount detected"** warnings from root detector apps

You can consider using [rvmm-zygisk-mount](https://github.com/j-hc/rvmm-zygisk-mount)

## Credits
- [j-hc](https://github.com/j-hc) for creating this amazing builder.
- [PeterMuller](https://github.com/peternmuller) for some things.
- And of course, the [ReVanced](https://github.com/ReVanced) team, [anddea](https://github.com/anddea), and the [Morphe](https://github.com/MorpheApp) team for their work on the ReVanced/Morphe apps!

## License
    Copyright (C) 2024-2026 Tanjidul Hossain

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program. If not, see <https://www.gnu.org/licenses/>.
