# EQUATIONSIX Interface

## Accessing the EQUATIONSIX Interface

To access the EQUATIONSIX Interface, use an IPFS gateway link from the
[latest release](https://github.com/EQUATIONSIX/EQUATIONSIX-interface/releases/latest), 
or visit [app.EQUATIONSIX.org](https://app.EQUATIONSIX.org).

## Development

### Install Dependencies

```bash
yarn
```

### Run

```bash
yarn start
```

### Configuring the environment (optional)

To have the interface default to a different network when a wallet is not connected:

1. Make a copy of `.env` named `.env.local`
2. Change `REACT_APP_NETWORK_ID` to `"{YOUR_NETWORK_ID}"`
3. Change `REACT_APP_NETWORK_URL` to e.g. `"https://{YOUR_NETWORK_ID}.infura.io/v3/{YOUR_INFURA_KEY}"` 

Note that the interface only works on testnets where both 
[EQUATIONSIX V2](https://EQUATIONSIX.org/docs/v2/smart-contracts/factory/) and 
[multicall](https://github.com/makerdao/multicall) are deployed.
The interface will not work on other networks.

## Contributions

**Please open all pull requests against the `master` branch.** 
CI checks will run against all PRs.

## Accessing EQUATIONSIX Interface V1

The EQUATIONSIX Interface supports swapping against, and migrating or removing liquidity from EQUATIONSIX V1. However,
if you would like to use EQUATIONSIX V1, the EQUATIONSIX V1 interface for mainnet and testnets is accessible via IPFS gateways 
linked from the [v1.0.0 release](https://github.com/EQUATIONSIX/EQUATIONSIX-interface/releases/tag/v1.0.0).
