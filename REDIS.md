# Redis

Here are the steps to install Redis on an Ubuntu system:

#### First, update the package manager's cache by running:
    sudo apt-get update

#### Next, install Redis by running:
    sudo apt-get install redis-server

#### Once the installation is complete, start the Redis server by running:
    sudo systemctl start redis

#### To enable Redis to start automatically at boot, run:
    sudo systemctl enable redis

#### To check the status of the Redis server, run:
    sudo systemctl status redis

#### To stop the Redis server, run:
    sudo systemctl stop redis

#### To restart the Redis server, run:
    sudo systemctl restart redis
    
#### Install the Redis PHP extension:
sudo apt-get install php7.4-redis

#### Restart PHP-FPM:
sudo systemctl restart php7.4-fpm    

That's it! You should now have Redis installed and running on your Ubuntu system.
