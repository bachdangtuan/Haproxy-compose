#### Docker-compose HAproxy
##### Systems team ISofh - D4n9Tu4z

File docker-compose setup HA-Proxy for Project Isofh Company

### Run docker-compose

docker-compose up -d 



### Gen cert
sudo apt-get install openssl

openssl req -newkey rsa:2048 -nodes -keyout private.key -out csr.pem
openssl x509 -req -in csr.pem -signkey private.key -out <tên cer>.pem


#### Kiểm tra cert
openssl x509 -text -noout -in cert.pem
