# zip-updater
Easily update any addon or content from a link to a zip file !

### What is it ? ###
Basically, this script will download your bunch of zips, extract them into a temp folder, then move the extraction content to the desired folder and clean the zips. You also have the option to convert everything to lowercase (useful for SRCDS addons), and to backup the zips you downloaded to allow rolling back to a previous version. Ultimately, you can disable prompting to use it as a cronjob.

### Requirements ###
- You need that package : unzip 
Should work for anything else similar to this :
- 
- Your zipfiles must have different names to be all managed correctly

### How to use ###
- You'd better make a new folder for it : mkdir zip-updater && cd zip-updater
- Download the script : wget https://raw.githubusercontent.com/UltimateByte/zip-updater/master/zip-updater
- Edit the script fo fit your needs : nano zip-updater
- Make it executable : chmod +x zip-updater
- Run and enjoy : ./zip-updater

#### Important notes ####
All all your zips content must have the same folder structure, otherwise, copy zip-updater to zip-updater2, and edit the destination directory accordingly.

Please, feedback
