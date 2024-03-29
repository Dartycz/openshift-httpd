### Downloading docker image ###
FROM httpd:2.4

### Set default workdir ###
WORKDIR /usr/local/apache2/htdocs/

### Copying web page files ###
COPY index.html /usr/local/apache2/htdocs/
COPY logo.png /usr/local/apache2/htdocs/
COPY style.css /usr/local/apache2/htdocs/

### Set default port ###
EXPOSE 80

### Start apache serwer ###
CMD ["httpd", "-D", "FOREGROUND"]
