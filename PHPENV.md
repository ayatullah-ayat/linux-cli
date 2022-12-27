## Install php

#### install dependencies
sudo apt install software-properties-common ca-certificates lsb-release apt-transport-https 

### install ondrej/php
LC_ALL=C.UTF-8 add-apt-repository ppa:ondrej/php 

### install php versions

sudo apt install php8.1
sudo apt install php7.4
sudo apt install php5.6

### install extensions

sudo apt install php8.1-mysql php8.1-mbstring php8.1-xml php8.1-curl

### switch default php version
sudo update-alternatives --config php

### uninstalling php

sudo apt remove php5.6 
