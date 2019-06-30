# terra-bridge-eth-docker-client
Containerized client for Terra-Bridge-ETH

## Install
1. Install `docker` and `docker-compose`.

## Start Client
1. Populate .env based with rpc urls, bridge addresses and validator credential. `VALIDATOR_ADDRESS` must be mixed case and have valid checksum, `PRIVATE KEYS` need to be provided without '0x' prefix.
1. Run `docker-compose run -d bridge yarn client:start`.
