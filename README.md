# docker-control

# docker vpn + shell + ui pristup 

* kreira VPN klijentsku konekciju na dc1
* ssh i ui rade na IP adresi tunela i obezbjeđuju pristup docker hostu 


# start  

 > docker-compose -f docker-compose.yml up -d && docker-compose -f  services.yml  up -d


# stop & remove 

 > docker-compose -f services.yml  down  && docker-compose -f  docker-compose.yml  down

# pristup 
## ssh 

 > http://tunnel_ip:4200

## docker ui 

 > http://tunnel_ip:9000
