# zip-updater
Easily update any addon or content from a link to a zip file !

### What is it ? ###
Basically, this script will download your bunch of zips, extract them into a temp folder, then move the extraction content to the desired folder and clean the zips. You also have the option to convert everything to lowercase (useful for SRCDS addons), and to backup the zips you downloaded to allow rolling back to a previous version. Ultimately, you can disable prompting to use it as a cronjob.

### Requirements ###
- You need that package : unzip 
- Your zipfiles must have different names to be all managed correctly (if downloaded from github, they will take the name of the repository, don't worry).
- You must able to use your eyes and brain to read the comments into the configuration part of the script.

### How to use ###
- You'd better make a new folder for it : mkdir zip-updater && cd zip-updater
- Download the script : wget https://raw.githubusercontent.com/UltimateByte/zip-updater/master/zip-updater
- Edit the script fo fit your needs : nano zip-updater
- Make it executable : chmod +x zip-updater
- Run and enjoy : ./zip-updater

#### Important notes ####
Everything will be simply extracted to the destination folder, so your zip content must have a coherent folder structure, otherwise, make another copy of zip-updater and edit it accordingly.

##### Known issues #####
If whatever you're updating removed some files, this script is unable to know that, so they will remain in your destination folder. 

Hope you'll enjoy that script !

If it helped you, please consider making a donation for our community : http://www.mesnie.org/donation/

Otherwise, a simple feedback (positive or negative) is always welcome. 
