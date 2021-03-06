shell-scripts
=============
A collection of shell scripts and shell functions (mostly bash).

## metadata
* Documentation (English): https://wiki.natenom.com/w/Linux/KDE/Service_Menu/Remove_Special_Metadata
* Documentation (German): https://wiki.natenom.de/linux/kde/servicemenues/metainformationen2

## kvm
### backup_image.sh
* Documentation (English): https://wiki.natenom.com/w/Backupscript_for_KVM
* Documentation (German): https://wiki.natenom.de/linux/scripte/backup_images

## misc
### speedtest_query.sh
* Documentation (English): https://wiki.natenom.com/w/Speedtest_results
* Documenation (German): https://wiki.natenom.de/linux/scripte/speedtest_query

### pdfreduce.sh
Usage:
pdfreduce.sh directory

The scripts uses find to get all PDF files within directory. Then it checks whether
there is already a low quality variant of the PDF file; it not, it creates one and
checks if the file size is really slower than the file size of the original file.
If smaller the file gets copied next to the original file.
This script uses /tmp to generate the low quality variants which is better for your SSD in case
of /tmp being a tmpfs :)

## mobilephone
* Documentation (English): https://wiki.natenom.com/w/Linux/KDE/Service_Menu/Mobile_music
* Documentation (German): https://wiki.natenom.de/linux/kde/servicemenues/mobile_music

## mumble
### startmumble.sh
* Documentation (English): https://wiki.natenom.com/w/Mumble-Starter_shell_script
* Documentation (German): https://wiki.natenom.de/mumble/tools/mumble-starter

### getmumbleurl.sh
* Documentation (English): https://wiki.natenom.com/w/Linux/Shell-Functions/getmumbleurl
* Documentation (German): https://wiki.natenom.de/linux/shell-funktionen/getmumbleurl

### push_murmur.sh
* Documentation (English): https://wiki.natenom.com/w/Push_murmur.sh
* Documentation (German): https://wiki.natenom.de/mumble/tools/push_murmur

### km.sh ###
* Documentation (English): https://wiki.natenom.com/w/Mumble-Starter_shell_script#Graphical_User_Interface_for_the_starter_script
* Documentation (German): https://wiki.natenom.de/mumble/tools/mumble-starter#grafisches_interface_fuer_das_script

## psi
* Documentation (English): https://wiki.natenom.com/w/Push_song_information
* Documentation (German): https://wiki.natenom.de/linux/shell-funktionen/push_song_information
