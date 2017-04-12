#!/bin/bash
rpm -Uvh https://mirror.webtatic.com/yum/el6/latest.rpm && yum update -y && yum install -y php56w php56w-fpm php56w-mbstring php56w-gd php56w-dom php56w-pdo php56w-mysqlnd php56w-mcrypt php56w-process php56w-pear php56w-cli php56w-xml php56w-curl php56w-pecl-memcached php56w-devel php56w-pecl-redis
