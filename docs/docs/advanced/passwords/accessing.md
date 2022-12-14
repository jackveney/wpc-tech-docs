# Accessing Password Repository

This article details accessing the KeePass password database. You must have KeePass installed your maching and the login information for both the WebDav server and the database. See below for the steps to access the database.

---

## 1. Open KeePass
  Open KeePass on your machine. If you do not have it installed, please [follow the installation instructions here](https://keepass.info/download.html). <i>Please note that KeePass is a Windows only software.</i>
  <br><img src="../assets/accessing/1200px-KeePass_icon.svg.png" alt="KeePass Icon" style="width:200px;"/>

## 2. Open from URL
  Verify (or enter) the following details into the "Open from URL" text boxes:
  <br>**URL:** ```https://restricted.wpctechdocs.info/passwords/WPC_Tech_Passwords.kdbx```
  <br>**User name:** *```(see information on hidden password magnet)```*
  <br>**Password:** *```(see information on hidden password magnet)```*
  <br>**Remember:** *```Do not remember username and password```*
  <br>*For security purposes, please do not let it remember anything other than the URL. We store sensitive data about our setup on the server and it would let people access that data who shouldn't be able to.*
  <br><img src="../assets/accessing/open_from_url.png" alt="Open from URL Prompt"/><br> 

### ***NOTE:*** If you do not automatically get the "Open from URL" prompt, click ```Cancel``` if there's a different prompt, otherwise click ```File >> Open >> Open URL...```

## 3. Open Database - WPC_Tech_Passowrds.kdbx
  Verify (or enter) the following details into the "Open Database - WPC_Tech_Passowrds.kdbx" text boxes:
  <br>**Master password:** *```(see information on hidden password magnet)```*
  <br>**Key file/provider:** ```WPC_Tech_Passwords.keyx```
  <br>*For security purposes, both of these are required to login to the password database. The key file is called ```WPC_Tech_Passwords.keyx``` and should be located on your computer somewhere. Search for it using the folder icon to the right of the dropdown. On the sanctuary computer the key file is located in the ```Documents``` folder. If you have lost this file, there is a backup located in the backups folder. [See this article on restoring the key file.](../backups/passwords/security_key.md)*
  <br><img src="../assets/accessing/open_database.png" alt="Open Database Prompt"/>

## 4. Finishing Up
  Provided that you have entered everything correctly, you should now be logged into the password database. (See the image below for a successful login example.) You can follow any of the following articles for more infomation on navigating the password database.

### [Navigating Database](navigating.md)
  View credentials in the password reposity by following the steps in [this article](viewing.md).

### [Viewing Credentials](viewing.md)
  View credentials in the password reposity by following the steps in [this article](viewing.md).

### [Adding Credentials](adding.md)
  Add credentials in the password reposity by following the steps in [this article](adding.md).

### [Editing Credentials](editing.md)
  Edit credentials in the password repository by following the steps in [this article](editing.md).

### [Deleting Credentials](removing.md)
  Delete credentials in the password repository by following the steps in [this article](removing.md).

  <br><img src="../assets/accessing/keepass_logged_in.png" alt="Successful Login"/>