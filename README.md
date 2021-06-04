# Cloudera 6.2.0 in CentOS7 for WSL2
The file is above 25MB, so i have to upload the file to my google cloud. use 7z to extract the file which is nearly 4.5GB tar.gz https://drive.google.com/file/d/1-B9yQOVG3OjdhWn2EvxRMzv9iLJ-9NbH/view?usp=sharing

Just simple import to wsl using command wsl --import <name_for_this_distro> <local_directory> <this_package> --version 2

then run using the command wsl -d <name_for_this_ditro>

then try to execute systemctl status.
