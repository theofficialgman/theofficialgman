### Hi there 👋

You might know me from the [Switchroot](https://discord.gg/N9PPYXjWMY), [Linux 4 Switch](https://discord.gg/53mtKYt), [L4T-Megascript](https://discord.gg/abgW2AG87Z), or [Botspot Software](https://discord.gg/RXSTvaUvuu) discord servers. I am a Linux enthusiast with a special love for ARM hardware (like my Nintendo Switch).

The Nintendo Switch is a Tegra-X1 based video game console. Nvidia produced Ubuntu Bionic 18.04 images (called [Jetpack](https://developer.nvidia.com/embedded/jetpack-archive)) for their Tegra-X1 Jetson hardware. Since that version of Ubuntu is out of standard support and not well supported, I ported Ubuntu Jammy 22.04 and Noble 24.04 to the Nintendo Switch. Users can install these distributions following the [Switchroot Ubuntu Jammy](https://wiki.switchroot.org/wiki/linux/l4t-ubuntu-jammy-installation-guide) and [Switchroot Ubuntu Noble](https://wiki.switchroot.org/wiki/linux/l4t-ubuntu-noble-installation-guide) installation guides.

Linux software support is very good for ARM in the official OS repositories (eg: apt under Debian/Ubuntu, and dnf on Fedora) but is lacking on other open source projects that are not in OS repositories. You can find a few of my ARM porting projects linked below for software that I wanted to run but wasn't available. Many of these applications and programs are available through the [L4T-Megascript](https://github.com/cobalt2727/L4T-Megascript) and/or [Pi-Apps](https://pi-apps.io/):

- [L4T-Megascript](https://github.com/cobalt2727/L4T-Megascript) - All-in-one installer and updater for popular programs on [L4T Ubuntu Noble 24.04](https://wiki.switchroot.org/wiki/linux/l4t-ubuntu-noble-installation-guide), [L4T Ubuntu Jammy 22.04](https://wiki.switchroot.org/wiki/linux/l4t-ubuntu-jammy-installation-guide), and [L4T Ubuntu Bionic 18.04](https://wiki.switchroot.org/wiki/linux/l4t-ubuntu-bionic-installation-guide) with no prior knowledge of Linux needed
- [Pi-Apps](https://github.com/Botspot/pi-apps) - Raspberry Pi (and a growing number of other ARM computers) App Store for Open Source Projects
- [Github Desktop](https://github.com/shiftkey/desktop/pull/897) - Github Desktop is a GUI git client. I wrote GitHub Actions based CI for ARM32/ARM64 Linux for Desktop and its dependencies
- [Nintendo Switch RetroPie Binaries](https://github.com/theofficialgman/RetroPie-Binaries) - Automatically built and hosted binaries for common libretro emulators to make installing RetroPie on Switch faster
- [Minecraft Java GDLauncher](https://github.com/Pi-Apps-Coders/files/releases/tag/large-files) - A simple, yet powerful Minecraft launcher with a strong focus on the user experience. Ported to ARM32/ARM64
- [Minecraft Java Prism Launcher](https://prismlauncher.org/download/linux/#debian-pi-os-ubuntu-(arm3264)) - An Open Source Minecraft launcher with the ability to manage multiple instances, accounts and mods. Focused on user freedom and free redistributability. Provides DEBs for Bionic/Buster and newer distros. Built and added ARM32/ARM64 Minecraft Dependencies to meta repo.
- [Minecraft Java ARM32 Manifest](https://github.com/theofficialgman/piston-meta-arm32) - An alternative to the official Minecraft manifest with ARM32 Linux support.
- [Minecraft Java ARM64 Manifest](https://github.com/theofficialgman/piston-meta-arm64) - An alternative to the official Minecraft manifest with ARM64 Linux support.
- [MuseScore 4](https://github.com/musescore/MuseScore/pulls?q=is%3Apr+is%3Aclosed+author%3Atheofficialgman) - MuseScore is an open source and free music notation software. Ported (source changes included now upstream) and compiled AppImages for ARM32/ARM64 Linux support (also works on Chromebooks).

If you would like to donate as a way of saying thanks, I have a [GitHub Sponsors profile](https://github.com/sponsors/theofficialgman).
