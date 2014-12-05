update-accelerator
==================

Update Accelerator (for IPCOP) from http://blockouttraffic.de/ua_index.php but holds my additions to the set of data cached

- update the 'updxlrator' file by copying the template and then changing 'vendor' information
- create a new 'gif' file called 'updxl-src-<vendor>.gif'
- upload new 'updxlrator' file to /usr/sbin, ensuring correct file attributes (chmod 755 updxlrator)
- upload 'updxl-src-<vendor>.gif' to /home/httpd/html/images/
- restart Update Accelerator from IPCop GUI
