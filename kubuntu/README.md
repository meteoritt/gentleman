Привет, твой логотип RickeyStar разошелся на бренд расширений для браузеров и окружений пользователя. Посвящается Алёне Чудаковой ( Lafrecia )

https://chromewebstore.google.com/detail/cdbfpkficciaijflbdpciioakpdlifim?utm_source=item-share-cp

https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://sergos.medium.com/git-flow-presentation-b80643390888&ved=2ahUKEwj9iL7_kJ-NAxVkFhAIHYw1OlUQFnoECCEQAQ&usg=AOvVaw1K9owWw9cVozFaOJ8YJ2OD

https://store.kde.org/u/CSRedRat

https://store.kde.org/p/1671317

https://github.com/ruopsdev

https://t.me/ruopsdev

https://medium.com/ruopsdev

# Distributive

## Kubuntu

Official Ubuntu flavour with KDE: customizable, functionality with solid design on Qt technologies for effective work and complete GUI experience.
Work out of the box, perfect in skillful hands. Best choice if your switches from Windows/Mac OS X.
*For skeptics. It makes sense to try again, if you judge from the experience of working with previous generations of KDE 3 & 4, the project has reached a qualitatively new level of technology and is the most lightweight and fast-acting DE, since consumes less memory after system start than Xfce/LXDE.*

### PPA

``` bash
sudo add-apt-repository ppa:kubuntu-ppa/ppa ## fresh KDE soft
sudo add-apt-repository ppa:network-manager/trunk ## daily build NetworkManager
sudo add-apt-repository ppa:ubuntu-x-swat/x-updates ## updated versions of X.org drivers
sudo apt-add-repository ppa:graphics-drivers/ppa ## newest Nvidia GeForce GPU proprietary drivers
```

Give all keys for added repository:

``` bash
sudo apt-key adv --recv-keys --keyserver keyserver.ubuntu.com `sudo apt-get update 2>&1 | grep -o '[0-9A-Z]\{16\}$' | xargs`
```

## openSUSE

Best GUI admin interface - Yast 2. Simplest package manager syntax - zypper (RPM).

## Fedora

RPM-based distro to learn Red Hat Enterprise Linux (RHEL)/CentOS and GNOME at Home.

## Debian

Most stable distributive.

## Calculate

Based on Gentoo, build packages from source.

## Manjaro/Chakra

Rolling updates, based on ArchLinux.

## Alpine

Small. Simple. Secure. Alpine Linux is a security-oriented, lightweight Linux distribution based on musl libc and busybox. For minimal Docker images.

## Busybox

Software suite that provides several Unix utilities in a single executable file.

## GParted

Disk Partition Manager utility.

# Desktop Environment

## KDE

Developed on Qt framework. Perfect designed UI-constructor with elaborated style.

Most popular distros with KDE by default:
* Kubuntu - Ubuntu-based with deb-packages, looking very nice for anyone, even demanding, user.
* openSUSE - well cooked and looks organic.
* Chakra - ArchLinux-based with a focus on KDE and Qt software, utilizing a unique half-rolling release model.
* KDE neon - Ubuntu-based powered KDE developers.
* Netrunner - Debian-based from BlueSystems Company - KDE patron and Kubuntu supporter.
* KaOS - tightly integrated rolling and transparent distribution, build from scratch with focus on KDE Plasma, Qt, x86\_64.

* Tiling: Win (Super) + Arrow or Mouse move windows strongly to the edge of the screen.
* Open terminal: Ctrl+Alt+T
* Run command: Alt+F2

### Emulator

- Yakuake - Quake-style enchansed functionality terminal emulator for KDE (Ctrl + \`)
- Terminator - tiling window

### MacOS X style

Light and stable DE with simple appearance and many features. Work with [xrdp](https://github.com/neutrinolabs/xrdp).