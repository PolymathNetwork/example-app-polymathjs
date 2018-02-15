![Polymath](Polymath.png)

[Read the whitepaper](whitepaper.pdf)

# Polymath Example Polymathjs app 

A boilerplate create-react-app example using the polymathjs npm module.

In order to get the example running, clone this repo onto your local machine. 

Then run `npm install` in the same folder as the `package.json`

After that, run npm start. Once the app is running, go into the browsers development console, and see the results of the calls we use from the polymathjs npm module. The code written can be found in App.js in the componentDidMount() function. 

## How the example app works

The example app is using the npm module for polymathjs. This allows you to use a javascript library, which connects to all possible function calls from the [polymath core](https://github.com/PolymathNetwork/polymath-core) contracts.

The library can automatically detect if you are on the testnet or the mainnet. If you are using metamask and you choose one of the networks, all function calls will be directed to the following contract addresses:


## Live on Ethereum Mainnet

| Contract                                                         | Address                                                                                                                       |
| ---------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| [PolyToken](./contracts/PolyToken.sol)                           | [0x9992eC3cF6A55b00978cdDF2b27BC6882d88D1eC](https://etherscan.io/address/0x9992eC3cF6A55b00978cdDF2b27BC6882d88D1eC) |
| [Compliance](./contracts/Compliance.sol)                         | [0x076719c05961a0c3398e558e2199085d32717ca6](https://etherscan.io/address/0x076719c05961a0c3398e558e2199085d32717ca6) |
| [Customers](./contracts/Customers.sol)                           | [	0xeb30a60c199664ab84dec3f8b72de3badf1837f5](https://etherscan.io/address/0xeb30a60c199664ab84dec3f8b72de3badf1837f5) |
| [SecurityTokenRegistrar](./contracts/SecurityTokenRegistrar.sol) | [0x56e30b617c8b4798955b6be6fec706de91352ed0](https://etherscan.io/address/0x56e30b617c8b4798955b6be6fec706de91352ed0) |


## Live on Ropsten testnet

| Contract                                                         | Address                                                                                                                       |
| ---------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| [PolyToken](./contracts/PolyToken.sol)                           | [0x96a62428509002a7ae5f6ad29e4750d852a3f3d7](https://ropsten.etherscan.io/address/0x96a62428509002a7ae5f6ad29e4750d852a3f3d7) |
| [Compliance](./contracts/Compliance.sol)                         | [0xc7cff0abbdb57ed2204077d53836bcfbd05fe474](https://ropsten.etherscan.io/address/0xc7cff0abbdb57ed2204077d53836bcfbd05fe474) |
| [Customers](./contracts/Customers.sol)                           | [0x6ae8cb236a2badec68c030c9cef252a68989002f](https://ropsten.etherscan.io/address/0x6ae8cb236a2badec68c030c9cef252a68989002f) |
| [SecurityTokenRegistrar](./contracts/SecurityTokenRegistrar.sol) | [0x86535a0f5d0fa9552295b021ff95bca3fb74f523](https://ropsten.etherscan.io/address/0x86535a0f5d0fa9552295b021ff95bca3fb74f523) |

## Contributing

We're always looking for developers to join the polymath network. To do so we
encourage developers to contribute by creating Security Token Offering contracts
(STO) which can be used by issuers to raise funds. If your contract is used, you
can earn POLY fees directly through the contract, and additional bonuses through
the Polymath reserve fund.

If you would like to apply directly to our STO contract development team, please
send your resume and/or portfolio to careers@polymath.network.

### Styleguide

The polymath-core repo follows the style guide overviewed here:
http://solidity.readthedocs.io/en/develop/style-guide.html

[polymath]: https://polymath.network
[ethereum]: https://www.ethereum.org/
[solidity]: https://solidity.readthedocs.io/en/develop/
[truffle]: http://truffleframework.com/
[testrpc]: https://github.com/ethereumjs/testrpc