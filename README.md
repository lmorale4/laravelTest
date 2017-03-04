# laravelTest
Playing around with laravel 5.4

This will be my attempt to make a random site and explaining every step of it.

## What I'm using
---
* LAMP Server
  * Linux, Apache, MySQL, PHP
* Laravel 5.4
* Bootstrap

## LAMP 
---

If you are using Windows, you'll need [VirtualBox](https://www.virtualbox.org/)
  * Remeber, Google and YouTube are your friends!

I'm using Ubuntu 16.04 so Linux is already set up. To set up the rest of LAMP, see the following sites

* [How To Install Linux, Apache, MySQL, PHP (LAMP) stack on Ubuntu](https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-on-ubuntu)

* [How To Ubuntu](http://howtoubuntu.org/how-to-install-lamp-on-ubuntu)

## Laravel
---

You can find all of the following instructions here: [Laravel](https://laravel.com/)
  * Once on the site, navigate to Documentation on the navbar

### 1. Composer

* You can download composer here: [Composer](https://getcomposer.org/download/)
* Or run the following commands in your command-line

```bash
php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
php -r "if (hash_file('SHA384', 'composer-setup.php') === '55d6ead61b29c7bdee5cccfb50076874187bd9f21f65d8991d46ec5cc90518f447387fb9f76ebae1fbbacf329e583e30') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
php composer-setup.php
php -r "unlink('composer-setup.php');"
```

### 2. Laravel 

* Download Laravel

```bash
composer global require "laravel/installer"
```

### 3. Create New Laravel Project

* Run

```bash
composer create-project --prefer-dist laravel/laravel [project-name]
```

  * in this case
  
  ```bash 
  composer create-project --prefer-dist laravel/laravel laravelTest
  ```
  
That is pretty much it. You can get started now.
