```
cp .env.sample .env
```

Update private key & account & web3 api key in .env file

```
docker-compose up
```

## run with multiple instances

```
 docker-compose up --scale guardian-guardian-service=2

```

Below are the service can be run with scale
- guardian-guardian-service
- guardian-ipfs-client
- guardian-worker-service



docker cp -a guardian-docker-compose-guardian-worker-service-1:/usr/worker-service/dist tmp/worker-service 
