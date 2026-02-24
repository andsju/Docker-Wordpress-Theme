# Docker Wordpress 

Using Docker official Wordpress image

https://hub.docker.com/_/wordpress?uuid=07B84D21-2808-4BB5-9FEA-FBB52ADFC784


Volumes settings in **docker-compose.yml**

```yml
    volumes:
      - ./wordpress:/var/www/html
```


## Access Wordpress

Visit http://localhost:8080


## Wordpress themes folder

`wordpress/wp-content/themes/`

Default theme name **underscores-me** generated from https://underscores.me/ 


## Use phpMyAdmin

Visit http://localhost:8081


## Use ftp

Visit http://localhost:21