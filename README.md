# BitSwap (Core) ⚡

Exchange for RGB assets

**Disclaimer**: Alpha Software

### How Works?

The user can participate of Pools and earn BTC or USDT like on Uniswap

How there's no lunch free, you can lose sats in these scenarios:

- Illiquid asset

- Stop Loss

- Channel Liquidity on Lightning Network

- DLC fail

### Swaps

- Alice create invoice (RGB or LN) for Bob receive USDT

- Bob receive USDT tokens of Alice

- Alice receive BTC of Bob

## Demo and PoC

We create our demo around DEX

[Demo video](https://github.com/BitSwap-BiFi/Bitswap-PoC/)

## Roadmap

- [ ] Add new pairs for dCHF, RGBTC and RGBEX tokens
- [ ] Mainnet
- [ ] Beta app
- [ ] UI/UX
- [ ] Official USDT implementation
- [ ] Integration with APIs from [RGBex](https://rgbex.io/)

## Run BitSwap

### Add to the your Cargo

You can add in your cargo.toml

```cargo.toml
[package]
rgb-core = "0.10.6"
rust-dlc = "0.4"
bitswap = "1.0.6"
rust-aluvm = "0.10.4"
rust-baid58 = "0.1.0"
rust-lightning = "0.0.116"
```
### Via CLI Command

Soon

## License

Licensed under either:

-  Apache License, Version 2.0 
-  MIT License
-  GNU General Public License v3.0


