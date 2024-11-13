# SelfHosted-DNS-Docker

Create Docker Network:
```
docker network create --subnet=172.16.0.0/24 dns_network
```

How to run:
1. Start PowerDNS Docker
2. Start Pihole Docker
3. Start Dnsdist Docker
