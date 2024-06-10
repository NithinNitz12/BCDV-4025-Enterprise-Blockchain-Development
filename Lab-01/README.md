# Lab 1 - Install and run simple network

## Cloning the repo and downloads fabric binaries and docker images
```bash
$ git clone https://github.com/lley154/fabric-samples.git
$ cd fabric-samples
$ ./bootstrap.sh
```

![Alt Text](./images/1.png)
![Alt Text](./images/2.png)
![Alt Text](./images/3.png)

## Start the Hyperledger Fabric test network with Certificate Authorities (CAs) enabled.
```bash
$ cd test-network
$ ./network.sh up -ca
$ docker ps -a
```
![Alt Text](./images/4.png)
![Alt Text](./images/5.png)

## Stop and remove the Hyperledger Fabric test network
```bash
$ ./network.sh down
```
![Alt Text](./images/6.png)