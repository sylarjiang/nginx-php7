Nginx and PHP for Docker

## Last Version
nginx: **1.11.5**   
php:   **7.0.12**

## test project
readme 

## Volumes
If you want to link to your web site directory on the docker host to the container run:
```sh
docker run --name web-code -p 8080:80 -v /your_code_directory:/data/www -d nginx-php7_container-name
```



You can see the **[wiki]()**

## [ChangeLog](changelogs.md)

## Thanks
[Legion]()  

## Author
Author: sylar    
Email:  5246396@      qq.com
Link:   
