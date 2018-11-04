# RavencoinJS (ravencoinjs-lib)

A javascript Ravencoin library for node.js and browsers based on BitcoinJS.

Released under the terms of the [MIT LICENSE](LICENSE).

## Should I use this in production?
Probably not! But its not much different from BitcoinJS... use at your own risk!

## Usage

**NOTE**: If you expect this library to run on an iOS 10 device, ensure that you are using [buffer@5.0.5](https://github.com/feross/buffer/pull/155) or greater.

### Typescript or VSCode users
Type declarations for Typescript [are available](https://github.com/DefinitelyTyped/DefinitelyTyped/tree/0897921174860ec3d5318992d2323b3ae8100a68/types/bitcoinjs-lib) for version `^3.0.0` of the library.

``` bash
npm install @types/bitcoinjs-lib
```

For VSCode (and other editors), it is advised to install the type declarations, as Intellisense uses that information to help you code (autocompletion, static analysis).

**WARNING**: These Typescript definitions are not maintained by the maintainers of this repository, and are instead maintained at [DefinitelyTyped](https://github.com/DefinitelyTyped/DefinitelyTyped).
Please report any issues or problems there.


### Flow
[Flow-type](https://flowtype.org/) definitions for are available in the [flow-*typed* repository](https://github.com/flowtype/flow-typed/tree/master/definitions/npm/bitcoinjs-lib_v2.x.x) for version `^2.0.0` of the library.

You can [download them directly](https://github.com/flowtype/flow-typed/blob/master/definitions/npm/bitcoinjs-lib_v2.x.x/flow_v0.17.x-/bitcoinjs-lib_v2.x.x.js), or using the flow-typed CLI:

``` bash
npm install -g flow-typed
flow-typed install -f 0.27 bitcoinjs-lib@2.2.0
```

These definitions are maintained by [@runn1ng](https://github.com/runn1ng).

## Contributing
See [CONTRIBUTING.md](CONTRIBUTING.md).

### Running the test suite

``` bash
npm test
npm run-script coverage
```

## Complementing Libraries
- [BIP21](https://github.com/bitcoinjs/bip21) - A BIP21 compatible URL encoding library
- [BIP38](https://github.com/bitcoinjs/bip38) - Passphrase-protected private keys
- [BIP39](https://github.com/bitcoinjs/bip39) - Mnemonic generation for deterministic keys
- [BIP32-Utils](https://github.com/bitcoinjs/bip32-utils) - A set of utilities for working with BIP32
- [BIP66](https://github.com/bitcoinjs/bip66) - Strict DER signature decoding
- [BIP68](https://github.com/bitcoinjs/bip68) - Relative lock-time encoding library
- [BIP69](https://github.com/bitcoinjs/bip69) - Lexicographical Indexing of Transaction Inputs and Outputs
- [Base58](https://github.com/cryptocoinjs/bs58) - Base58 encoding/decoding
- [Base58 Check](https://github.com/bitcoinjs/bs58check) - Base58 check encoding/decoding
- [Bech32](https://github.com/bitcoinjs/bech32) - A BIP173 compliant Bech32 encoding library
- [coinselect](https://github.com/bitcoinjs/coinselect) - A fee-optimizing, transaction input selection module for bitcoinjs-lib.
- [merkle-lib](https://github.com/bitcoinjs/merkle-lib) - A performance conscious library for merkle root and tree calculations.
- [minimaldata](https://github.com/bitcoinjs/minimaldata) - A module to check bitcoin policy: SCRIPT_VERIFY_MINIMALDATA

## LICENSE [MIT](LICENSE)
