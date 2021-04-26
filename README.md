# rpi-debs
Debian APT repository for misc packages not yet available in Raspberry Pi OS. This repo contains the build scripts and installation instructions. The APT repo itself is hosted on [PackageCloud](https://packagecloud.io/).

## Installing
To add the repository to your system, do:
```sh
curl -s https://packagecloud.io/install/repositories/Alvarito050506/rpi-debs/script.deb.sh | sudo bash
```

After that, you can install any of the packages listed here normally:
```sh
# Replace PACKAGE_NAME with a valid package name (e.g. adoptopenjdk-16-jdk)
sudo apt install PACKAGE_NAME
```

## List of packages
 + `adoptopenjdk-16-jdk`: AdoptOpenJDK build including the entire JDK (no JRE, since it's not necessary, but it could be generated).
