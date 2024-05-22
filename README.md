# m2-docker

<VirtualHost *:80>
    ServerName webapp.test.local
    
    ProxyPass / http://webapp:8080/
    ProxyPassReverse / http://webapp:8080/
    ProxyRequests Off
</VirtualHost>