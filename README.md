# OILX Token

## Overview

OILX is a token designed to mirror the price movements of NYMEX crude oil. It provides investors with a unique opportunity to participate in the crude oil market without the complexities of traditional investment methods.

## Smart Contracts

The smart contract for OILX is written in FunC and deployed on the TON blockchain.

## Token Details

- **Name:** OILX
- **Symbol:** OILX
- **Total Supply:** 30 trillion OILX tokens

## Usage

### Checking Balance

```sh
tonos-cli call <contract_address> balanceOf '{"account": "<user_address>"}' --abi OILXToken.abi.json
```

### Transferring tokens

```sh
tonos-cli call <contract_address> transfer '{"amount": "<amount>", "to": "<recipient_address>"}' --abi OILXToken.abi.json --sign wallet.keys.json
```

### Contributing
Contributions are welcome! Please submit a pull request or open an issue to discuss improvements.


### Conclusion

By following these steps, you will ensure that your smart contracts are available on GitHub, your token is verified, listed on a DEX, and supported by popular wallets like Tonkeeper. This comprehensive approach will make your token more accessible and trustworthy to potential users and investors. If you need further assistance, feel free to ask!


