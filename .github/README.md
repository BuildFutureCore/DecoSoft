###### fireice-uk's and psychocrypt's
# XMR-Depricon - Cryptonight All-in-One Mining Software

XMR-Depricon is a universal Stratum pool miner. This miner supports CPUs, AMD and NVIDIA GPUs and can be used to mine the crypto currencies Monero, Aeon and many more Cryptonight coins.

## Overview
* [Features](#features)
* [Supported altcoins](#supported-altcoins)
* [Download](#download)
* [Usage](doc/usage.md)
* [HowTo Compile](doc/compile.md)
* [FAQ](doc/FAQ.md)
* [Developer Donation](#default-developer-donation)
* [Developer PGP Key's](doc/pgp_keys.md)

## Features

- support all common backends (CPU/x86, AMD-GPU and NVIDIA-GPU)
- support all common OS (Linux, Windows and macOS)
- supports algorithm cryptonight for Monero (XMR) and cryptonight-light (AEON)
- easy to use
  - guided start (no need to edit a config file for the first start)
  - auto-configuration for each backend
- open source software (GPLv3)
- TLS support
- [HTML statistics](doc/usage.md#html-and-json-api-report-configuraton)
- [JSON API for monitoring](doc/usage.md#html-and-json-api-report-configuraton)

## Supported altcoins

Besides [Monero](https://getmonero.org), following coins can be mined using this miner:

- [Aeon](http://www.aeon.cash)
- [BBSCoin](https://www.bbscoin.xyz)
- [BitTube](https://coin.bit.tube/)
- [Conceal](https://conceal.network)
- [Graft](https://www.graft.network)
- [Haven](https://havenprotocol.com)
- [Lethean](https://lethean.io)
- [Masari](https://getmasari.org)
- [Plenteum](https://www.plenteum.com/)
- [QRL](https://theqrl.org)
- **[Ryo](https://ryo-currency.com) - Upcoming xmr-stak-gui is sponsored by Ryo**
- [Stellite](https://stellite.cash/)
- [TurtleCoin](https://turtlecoin.lol)
- [Zelerius](https://zelerius.org/)
- [X-CASH](https://x-network.io/)

Ryo currency is a way for us to implement the ideas that we were unable to in
Monero. See [here](https://github.com/fireice-uk/cryptonote-speedup-demo/) for details.

If your prefered coin is not listed, you can choose one of the following algorithms:
- 256Kib scratchpad memory
    - cryptonight_turtle
- 1MiB scratchpad memory
    - cryptonight_lite
    - cryptonight_lite_v7
    - cryptonight_lite_v7_xor (algorithm used by ipbc)
- 2MiB scratchpad memory
    - cryptonight
    - cryptonight_gpu (for Ryo's 14th of Feb fork)
    - cryptonight_masari (used in 2018)
    - cryptonight_v7
    - cryptonight_v7_stellite
    - cryptonight_v8
    - cryptonight_v8_double (used by X-CASH)
    - cryptonight_v8_half (used by masari and stellite)
    - cryptonight_v8_reversewaltz (used by graft)
    - cryptonight_v8_zelerius
- 4MiB scratchpad memory
    - cryptonight_haven
    - cryptonight_heavy

Please note, this list is not complete and is not an endorsement.

## Download

You can find the latest releases and precompiled binaries on GitHub under [Releases](https://github.com/fireice-uk/xmr-Depricon/releases).

## Default Developer Donation

By default, the miner will donate 2% of the hashpower (2 minutes in 100 minutes) to my pool. If you want to change that, edit [donate-level.hpp](xmrDepricon/donate-level.hpp) before you build the binaries.

If you want to donate directly to support further development, here is my wallet

fireice-uk:
```
4581HhZkQHgZrZjKeCfCJxZff9E3xCgHGF25zABZz7oR71TnbbgiS7sK9jveE6Dx6uMs2LwszDuvQJgRZQotdpHt1fTdDhk
```

psychocrypt:
```
45tcqnJMgd3VqeTznNotiNj4G9PQoK67TGRiHyj6EYSZ31NUbAfs9XdiU5squmZb717iHJLxZv3KfEw8jCYGL5wa19yrVCn
```
