## Load Balancer Solution With Nginx and SSL/TLS

1. Register a domain name on route 53

2. Create records with domain name 

3. Link route 53 with domain

`sudo apt update`

`sudo apt install nginx`

`sudo vi /etc/nginx/nginx.conf`

`sudo systemctl restart nginx`

`sudo systemctl status nginx`

`sudo systemctl status snapd`

`sudo snap install --classic certbot`

`sudo ln -s /snap/bin/certbot /usr/bin/certbot`

`sudo certbot renew --dry-run`

`crontab -e`

