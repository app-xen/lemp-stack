# APPXEN LEMP
--

 - Nginx
 - PHP 7.2-fpm
 - MySQL
 - Maildev

# Quickstart
--

## Services

 - Website: http://your-ec2-instance/
 - PhpMyAdmin: http://your-ec2-instance:8081
 - Mail catcher: http://yout-ec2-instance:8082
 - Logs: ~/log/
 - Environment Variables: ~/.env
## Use a virtual host

- On your instance, run `sudo nano /etc/hosts` and add `insert-ip-address insert-host-name`
- Change the server name in docker/nginx/nginx.conf#L3 to `insert-host-name`
- Modify .env and set SERVER_PORT=80
- Run `docker-compose up`

# Support
--

For support visit https://appxen.com/

Happy coding!
