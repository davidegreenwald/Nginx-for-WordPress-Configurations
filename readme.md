# Nginx WordPress Configurations

Nginx-only, Apache-free configurations for WordPress with PHP-FPM, FastCGI cache, SSL, security settings, .webp support, and phpMyAdmin (just in case!). Mix and match the .conf files for your preferred configuration and traffic needs.

## Testing and compatibility
This has been thoroughly tested with the Nginx 1.12 stable branch and PHP 7.2 in Ubuntu 16.04 and is up and running on several production sites.

## How to use
* Pick a /conf.d file and mix to taste. Check for #TODO for `example.com` fields that need editing.
* Drop nginx.conf and the rest of these folders into /etc/nginx on your Linux server.
* `sudo nginx -t` to check for typos
* `sudo systemctl reload nginx`
* You're live.

## In progress
Still working on nailing down logging, rate limiting, and a few other settings. Feel free to leave tips, suggestions, and pull requests.
