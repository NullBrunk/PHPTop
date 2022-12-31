<div align="center">

# PHPTop

A simple monitor written un PHP 

<br>

![GitHub top language](https://img.shields.io/github/languages/top/NullBrunk/PHPTop?style=for-the-badge)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/NullBrunk/PHPTop?style=for-the-badge)
![repo size](https://img.shields.io/github/repo-size/NullBrunk/PHPTop?style=for-the-badge)

![image](https://user-images.githubusercontent.com/106782577/210119720-9e506e44-7a26-46b3-825e-d7d507aa8f57.png)


</br>
## Features 

Cards   
- Display OS Name and Kernel version
- Display RAM usage every 2 seconds
- Display disk usage and total disk space
- Display the current uptime

Graph    
- Display a graph of the CPU usage 
- Display a Circular diagram of the RAM usage on the total RAM


# Installation

Install apache/nginx and PHP on your machine, then depending on your OS, go to /srv/http OR /var/www/html

```bash
git clone https://github.com/NullBrunk/PHPTop
cd PHPTop
mv * ..
cd .. && rm -r PHPTop
chmod 777 assets/scripts/cpu.txt assets/scripts/cpuusage.sh
```

Start the HTTP and the PHP service, and go to 127.0.0.1 
