# Use the default image. Do not use like those guys who use a Linux distro then install nginx
FROM nginx

# Add the configuration file of my Symfony project
ADD symfony.conf /etc/nginx/sites-available/
RUN mkdir /etc/nginx/sites-enabled
RUN ln -s /etc/nginx/sites-available/symfony.conf /etc/nginx/sites-enabled/symfony.conf
