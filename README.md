# SDDManga

## Screenshots

![image](https://github.com/user-attachments/assets/d09eb6cd-ae50-4ad2-8da4-8fbb53b43e54)


## Overview

SDDManga is a manga-themed SDDM login screen that’s here to turn your boring login into a full-on anime moment.

## Installation

### Backup Existing SDDM Theme

Before proceeding, back up your current SDDM theme:
```bash
sudo cp -r /usr/share/sddm/themes/your-current-theme ~/sddm-theme-backup
```
### Install SDDManga

1. Clone this repository to your local machine:
```
git clone https://github.com/not1cyyy/SDDManga.git ~/usr/share/sddm/themes/SDDManga
```
2. Set SDDManga as the default theme:

Edit the SDDM configuration file:
```bash
sudo nano /etc/sddm.conf
```
Add or modify the following lines:
```qml
[Theme]
Current=SDDManga
```
3. Restart SDDM to apply the changes:
```bash
sudo systemctl restart sddm
```
## Dependencies

Ensure you have the following installed:

- SDDM (Simple Desktop Display Manager)
- A compatible display server (X11 or Wayland)
