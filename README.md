# geth-poa-devnet
Test configuration for a Geth PoA private network

## Pre-requisites
```
cd config
docker-compose pull
```

## Initialize the nodes
```
docker-compose -f docker-compose_init.yaml up
```

## Run the network
```
docker-compose up
```
