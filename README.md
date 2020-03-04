# wpacrack
Automated shell script to crack WPA's password.

In order to run this script you must need to be a ROOT user!

You also need [Aircrack-ng](https://github.com/aircrack-ng/aircrack-ng) to crack WPA's handshake file.

Usage:
You can run the script after giving it a permission or add it to your /bin folder just to easy access.

Example:
```shell
#: chmod +x /path/to/your/WPACRACK
#: bash /path/to/your/WPACRACK
```
or
```shell
#: chmod +x /path/to/your/WPACRACK
#: mv /path/to/your/WPACRACK /root/WPACRACK
#: ./WPACRACK
```
or
```shell
#: chmod +x /path/to/your/WPACRACK
#: mv /path/to/your/WPACRACK /root/WPACRACK
#: mv WPACRACK /bin/WPACRACK
#: WPACRACK
```
The third case you can access without being root user, but it's recommended! Also you don't need to get into a specific folder to run it.

You also need to create a folder in your /root directory called 'WPACRACK'.
The WPA's handshake file can be recognized as 'WPACRACK.cap' inside 'WPACRACK' folder.
The wordlist file can be recognized as 'WORDLIST' inside 'WPACRACK' folder.
