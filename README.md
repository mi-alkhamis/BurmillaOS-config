[![GitHub license](https://img.shields.io/badge/dwsclass-ops--009-brightgreen?style=plastic)](https://github.com/mi-alkhamis/BurmillaOS-config)
[![GitHub license](https://img.shields.io/github/license/mi-alkhamis/BurmillaOS-config?color=Green&style=plastic)](https://github.com/mi-alkhamis/BurmillaOS-config/blob/main/LICENSE) [![GitHub issues](https://img.shields.io/github/issues/mi-alkhamis/BurmillaOS-config?style=plastic)](https://github.com/mi-alkhamis/BurmillaOS-config/issues)  [![GitHub stars](https://img.shields.io/github/stars/mi-alkhamis/BurmillaOS-config?style=plastic)](https://github.com/mi-alkhamis/BurmillaOS-config/stargazers)




# BurmillaOS Installation

# Intro

This config is used for BurmillaOS installation, I assume you are familiar with this type of OS, 
If you aren't, Read [THIS](https://burmillaos.org) first

# Prerequisites
 1. BurmillsOS iso from [BurmillaOS](https://burmillaos.org/#latest-release)
 2. I use Virtual Box for virtualization, YMMV
 3. START

# How to install
1. After booting os run `sudo su -`
2. Change rancher password `passwd rancher`
3. set your appropriate values in config.yaml file 
4. check your config file with `ros config validate -I config.yaml`
5. with root permission run `ros install -d /dev/sda -c config.yaml`
6. Congratulation, Your New OS has been installed. 

# Contribute
All contributions are welcome:
- Read the issues, fork the project and do a Pull Request.
- Request a new topic creating a New issue with the enhancement tag.
- Find any kind of errors in the cheat sheet and create a New issue with the details or fork the project and do a Pull Request.

# License

This project is licensed under the GPL-v3 License - see the [LICENSE](https://github.com/mi-alkhamis/BurmillaOS-config/edit/main/LICENSE) file for details.

[@dwsclass](https://github.com/dwsclass) dws-ops-009-rancheros
