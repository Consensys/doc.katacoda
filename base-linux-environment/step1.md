[Playground host](https://[[HOST_SUBDOMAIN]]-[[KATACODA_HOST]].environments.katacoda.com/)

List of a few projects that are known to work on this environment.

## Doc preview

https://consensys.net/docs/doctools/en/latest/preview/new-system/

```
git clone https://github.com/ConsenSys/doctools.template-site.git template-docsite
docker pull ghcr.io/consensys/doctools-builder:latest
cd template-docsite
docker-compose up -d
```
{{execute}}

<!--
## Hyperledger Besu

`docker run -p 8545:8545 hyperledger/besu:latest --miner-enabled --miner-coinbase fe3b557e8fb62b89f4916b721be55ceb828dbd73 --rpc-http-cors-origins="all" --host-allowlist="*" --rpc-http-enabled --network=dev`{{execute}}

and connect to HTTP RPC at https://[[HOST_SUBDOMAIN]]-8545-[[KATACODA_HOST]].environments.katacoda.com with Network ID `2018`

## Truffle tutorial

https://trufflesuite.com/tutorial/

Run `truffle dev` instead of using Ganache

Connect Metamask to https://[[HOST_SUBDOMAIN]]-7545-[[KATACODA_HOST]].environments.katacoda.com
-->
