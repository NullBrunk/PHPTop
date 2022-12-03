# PHPTop
A simple PHP monitor 

![image](https://user-images.githubusercontent.com/106782577/205441672-b3a40799-b643-4216-8311-5e11ed550054.png)


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
