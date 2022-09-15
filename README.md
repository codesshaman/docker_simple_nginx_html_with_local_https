### docker_simple_nginx_html_with_local_https
My training simple config with docker compose

Your need docker and docker-compose in your operation system.

CLONE:
``git clone https://github.com/codesshaman/docker_simple_nginx_html_with_local_https.git``

GO TO FOLDER:
``cd docker_simple_nginx_html_with_local_https``

Every commands executed into the folder with Makefile.

BUILD (first start): ``make build``

RUN: ``make``

STOP: ``make down``

COMMAND TO CONTAINER:
``docker exec -it simple_ssl_html <bash_command>``

SHELL INSIDE CONTAINER:
``docker exec -it simple_ssl_html sh``

OPEN:
``https://localhost/``
