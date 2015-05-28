# apache2_php

## Usage
To run the image
```sh
docker run -d -P --name apache2 chihhunglin/apache2-php
```
To see the port forwarding
```sh
docker port apache2
```
To login ssh container (password: root)
```sh
ssh root@localhost -p <host port>
```
