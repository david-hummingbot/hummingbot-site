This page contains notes about connecting Gateway to the Near Protocol.

## Near Protocol

📁 [Chain folder](https://github.com/hummingbot/gateway/tree/main/src/chains/near)

📁 [Config template](https://github.com/hummingbot/gateway/tree/main/src/templates/near.yml)

Below are the Near Protocol networks that Gateway currently supports.

### `mainnet` (near mainnet)

**Default configuration parameters**

* `chainID`: 0
* `nodeURL`: <https://rpc.mainnet.near.org>
* `tokenListType`: `FILE`
* `tokenListSource`: `src/chains/near/near_tokens.json`
* `nativeCurrencySymbol`: NEAR
* `gasPriceRefreshInterval`: 60

You can adjust these parameters by running the Hummingbot command:

```
gateway config near.networks.mainnet.<parameter>
```

### `testnet` (near testnet)

**Default configuration parameters**

* `chainID`: 0
* `nodeURL`: <https://rpc.testnet.near.org>
* `tokenListType`: `FILE`
* `tokenListSource`: `src/chains/near/near_testnet_tokens.json`
* `nativeCurrencySymbol`: NEAR
* `gasPriceRefreshInterval`: 60

You can adjust these parameters by running the Hummingbot command:

```
gateway config near.networks.testnet.<parameter>
```
