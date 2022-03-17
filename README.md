# Soul-packages
Package repository for Soul Linux. This is the official package repository for soulinux packages. It is pre-enabled by default on Soul Linux but can be also added to other Arch based distros by adding the following line in the /etc/pacman.conf file

[soullinux]
SigLevel = Optional TrustAll
Server = https://raw.githubusercontent.com/Soullinux/Soul-packages/main/$arch
