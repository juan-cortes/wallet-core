<!--- Thank you for requesting new blockchain support -->

<!--- Before submitting please check to see if this coin was already requested -->

<!--- Provide as many relevant details about the coin -->
## Description

<!-- Coin Name and official website e.g. [Bitcoin](https://bitcoin.org) -->
Name:
<!-- HD Derivation Scheme e.g. BIP44 / 0 -->
HD Derivation Scheme:
<!-- Symbol e.g. BTC -->
Symbol:
<!-- Documentation (Address / Transaction signing etc) and reference implementation links -->
Documentation:
<!-- Why we should support it? -->
Reason:

## Checklist

<!-- Sample Checklist -->

- [ ] Coin configuration
- - [ ] Add coin type / decimals
- - [ ] Recommended tx block explorer
- - [ ] Return correct curve and purpose in `src/interface/TWCoinType.cpp`.
- [ ] Address
- - [ ] Derivation from bip39 phrases
- - [ ] Derivation from public key / string
- - [ ] Implement address validation and conversion in `src/Addres.cpp`.
- [ ] Transaction
- - [ ] serialization / encoding
- [ ] Signer
- - [ ] signing input / output protobuf messages
- - [ ] signature
- [ ] C interfaces
- - [ ] TW[Blockchain]Address
- - [ ] TW[Blockchain]Transaction / TW[Blockchain]Signer
- [ ] Tests
- - [ ] Unit test
- - [ ] C Interface test ( Java / Swift)
- [ ] RPC documentation
- - [ ] query balance
- - [ ] query fee
- - [ ] query transaction list
- - [ ] query transaction detail
- - [ ] submit rawtx
- - [ ] blockchain info (block height)
