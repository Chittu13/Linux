# wget 
### Wget is the non-interactive network downloader which is used to download files from the server even when the user has not logged on to the system
- > first should download the wget in you system
```sudo apt install wget```
- >```wget -O kali.7z https://cdimage.kali.org/kali-2023.3/kali-linux-2023.3-virtualbox-amd64.7z```
- >```wget -P home/kali/Downloads kali.7z https://cdimage.kali.org/kali-2023.3/kali-linux-2023.3-virtualbox-amd64.7z```
- >```wget -c kali.7z https://cdimage.kali.org/kali-2023.3/kali-linux-2023.3-virtualbox-amd64.7z```
### -c refers to resume the download
- >```wget -i download.txt```
