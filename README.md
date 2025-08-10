## About
The script is designed to remove Snap packages and the Snapd service from an Ubuntu system and replace it with Firefox from Mozilla's APT repository. It first prompts the user for confirmation before removing Snap packages and the Snapd service, including stopping and disabling the Snapd service, purging the Snapd package, and deleting Snap-related directories. After Snap is removed, it creates a preference file to prevent Snapd from being reinstalled. The script then prompts the user again to confirm if they want to install Firefox, adds Mozilla’s APT repository, and installs Firefox. Lastly, it optionally installs the Gnome App Store if the user agrees. The script includes error handling to ensure each step completes successfully and provides feedback if something goes wrong.

## How To Run
1. _Save the Script_

   1-1. Download the script name **remove_snap.sh**

   1-2. ...or clone this repo : \
   ```git clone https://github.com/PagalSarthak/Remove-snap-in-ubuntu```


2. Open a terminal and navigate to the directory where you saved the script.

3. You need to make the script executable. You can do this using the chmod command : \
   ```chmod +x remove_snap.sh ```

4. Now that the script is executable, you can run it. \
   Use the following command **(MUST RUN WITH ROOT PRIVILEGE FOR APT)** : \
   ```sudo ./remove_snap.sh```

## Optional Install
- [Firefox](https://www.firefox.com/)
    - [Extended Support Release](https://wiki.mozilla.org/Enterprise/Firefox/ExtendedSupport:Proposal) or Rapid(Normal) Release
- [Gnome Software Center](https://apps.gnome.org/en/Software/)

## Which Ubuntu Version It Support?
It supports every Ubuntu version with snap until now.

## Disclaimer
Ubuntu is a registered trademark of Canonical Ltd.  
This project is not affiliated with, endorsed by, or sponsored by Canonical Ltd or the Ubuntu project.

---
**TAKE BACKUP OF SYSTEM AND USE AT YOUR OWN RISK**