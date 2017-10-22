# SwitchPhpVersion

# Default PHP 5.6 is set on your system and you need to switch to PHP 7.1.

Apache:-
    $ sudo apt-get install php7.1 libapache2-mod-php7.1
    $ sudo a2dismod php5.6
    $ sudo a2enmod php7.1
    $ sudo service apache2 restart
    
Command Line:-

    $ update-alternatives --set php /usr/bin/php7.1
    
From PHP 7.1 => PHP 5.6

# Default PHP 7.1 is set on your system and you need to switch to PHP 5.6.

Apache:-
    $ sudo apt-get install php5.6  php-gettext php5.6-mbstring php-xdebug libapache2-mod-php5.6
    $ sudo a2dismod php7.1
    $ sudo a2enmod php5.6
    $ sudo service apache2 restart
    
Command Line:-

    $ sudo update-alternatives --set php /usr/bin/php5.6
