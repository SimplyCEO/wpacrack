# wpacrack
Automated shell script to crack WPA's password.

In order to run this script you must need to be a ROOT user!

You also need [Aircrack-ng](https://github.com/aircrack-ng/aircrack-ng) to crack WPA's handshake file.

Usage:
You can run the script after giving it a permission or add it to your /bin folder just to easy access.

Example:
```shell
# chmod +x /path/to/your/wpacrack
# bash /path/to/your/wpacrack
```
or
```shell
# chmod +x /path/to/your/wpacrack
# mv /path/to/your/wpacrack /root/wpacrack
# ./wpacrack
```
or
```shell
# chmod +x /path/to/your/wpacrack
# mv /path/to/your/wpacrack /root/wpacrack
# mv wpacrack /bin/wpacrack
# wpacrack
```
The third case you can access without being root user, but it's recommended! Also you don't need to get into a specific folder to run it.
