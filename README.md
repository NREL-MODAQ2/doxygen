# doxygen
Repo for creating the c++ documentation for MODAQ2

Clone this repository to your ROS2 working directory (not in the src direcotry).

If docs are needed, install doxygen

sudo apt install doxygen

To build and install the docs run the following commands in terminal
```bash
cd doxygen/
doxygen
```

The docs will be put into the nginx web server folder can be read by opening {YOUR_IP_ADDRESS}/html/index.html in a browser

The user must own /var/www/html.

To implement: sudo mkdir /var/www/html sudo chown ${USER} -R /var/www/html