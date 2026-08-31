# NGINX-REVERSE-PROXY
NGINX &amp; LOADB BALANCE CODE
The given step's need to followed for set-up nginx

sudo dnf install nginx -y  (we need to install nginx )
systemctl restart nginx    ( restart the package manager of nginx )
systemctl status nginx     (check the status of nginx)
cd /ect/nginx/             (it is the default path of nginx )
ll or ls                   (get the list of nginx)
vi nginx.conf              (used editor to paste the private address) 
location /{
proxy_pass http:// Private IP address:port no/;
