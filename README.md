# macos-file-position
file position macos config environtment

## file hosts

    Macintosh HD => etc/hosts
    Can open be like sudo vim /etc/hosts

## folder sites-available

  Macintosh HD => usr/local/etc/nginx/sites-available
  
## folder sites-enabled

  Macintosh HD => usr/local/etc/nginx/sites-enabled
  
## PHP

  Macintosh HD => usr/local/etc/php/7.2
  
## command run magento 2
  + setup:upgrade:
    php -dmemory_limit=8G bin/magento set:up
## errors

  When met bug 404 not found site. Please change permission index.php file to 777 and var/pub/app
