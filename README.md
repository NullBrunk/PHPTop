# PHPTop
![image](https://user-images.githubusercontent.com/106782577/205441998-bc2ba2ee-da15-4c62-82a5-8228cc5cb0a5.png)

## Features 

Cards   
- Display OS Name and Kernel version
- Display RAM usage every 2 seconds
- Display disk usage on total disk
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
