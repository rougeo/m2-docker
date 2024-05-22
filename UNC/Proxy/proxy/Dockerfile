FROM ubuntu/apache2:2.4-20.04_beta
RUN apt-get update && apt-get install -y iputils-ping curl

RUN a2enmod proxy proxy_ajp proxy_http rewrite deflate headers proxy_balancer proxy_connect proxy_html