# cryptowallet-cli

> Crypto wallet generator CLI tool

![Screenshot](https://i.imgur.com/jaZ5SVi.png)

---

## Install
```bash
# via Yarn
$ yarn global add @yerofey/cryptowallet-cli

# or via NPM
$ npm i -g @yerofey/cryptowallet-cli
```

## Usage
```bash
# generate random ERC-like wallet (ETH, BNB, POLYGON, ...)
$ cryptowallet

# generate random ERC-like wallet with desired prefix
$ cryptowallet -p aaa

# generate random BTC wallet (default format: bech32 - bc1...)
$ cryptowallet -c BTC

# generate random BTC wallet with desired prefix (case sensitive)
$ cryptowallet -c BTC -p ABC

# generate random BTC wallet with desired prefix (case insensitive)
$ cryptowallet -c BTC -pi abc

# generate BTC legacy wallet (1...)
$ cryptowallet -c BTC -f legacy

# generate BTC segwit wallet (3...)
$ cryptowallet -c BTC -f segwit

# generate BTC bech32 wallet from mnemonic string
$ cryptowallet -c BTC -f bech32 -m "radio bright pizza pluck family crawl palm flame forget focus stock stadium"

# generate N of BTC bech32 wallets from mnemonic string
$ cryptowallet -c BTC -f bech32 -n 10 -m "radio bright pizza pluck family crawl palm flame forget focus stock stadium"

# generate ERC-like wallet from mnemonic string
$ cryptowallet -m "radio bright pizza pluck family crawl palm flame forget focus stock stadium"

# generate BNB (BEP2) wallet from mnemonic string
$ cryptowallet -c BNB -f BEP2 -m "radio bright pizza pluck family crawl palm flame forget focus stock stadium"

# generate BNB (BEP20) wallet from mnemonic string
$ cryptowallet -c BNB -f BEP20 -m "radio bright pizza pluck family crawl palm flame forget focus stock stadium"

# generate just a mnemonic string (12 words) to import in any wallet app
$ cryptowallet -mo

# list all supported cryptos
$ cryptowallet -l
```

## Cryptos supported
- `BTC` (Bitcoin) [legacy, segwit, bech32]
- `ETH` (Ethereum)
- `BNB` (Binance Coin) [BEP2, BEP20]
- `DOGE` (Dogecoin) [legacy, segwit, bech32]
- `BCH` (Bitcoin Cash)
- `LTC` (Litecoin) [legacy, segwit, bech32]
- `POLYGON` (Polygon)
- `TRX` (Tron) 
- `XTZ` (Tezos) 
- `DASH` (Dash) 
- `DCR` (Decred) 
- `ZEC` (Zcash) 
- `QTUM` (Qtum) 
- `BTG` (Bitcoin Gold) 
- `DGB` (DigiByte) 
- `RDD` (ReddCoin) 
- `VTC` (Vertcoin) 
- `MONA` (MonaCoin) 
- `NMC` (NameCoin) 
- `PPC` (PeerCoin) 
- `BLK` (BlackCoin) 
- `VIA` (Viacoin) 
- `NBT` (NIX Bridge Token) 

## Highlights
- 23 cryptos supported
- Desired wallet prefix
- Wallet from mnemonic
- Works fully offline

## TODO
- Show SegWit Bech32 BTC change addresses with additional flag
- SegWit Bech32 wallet address support for all Bitcoin forks
- More EVM compatible cryptos

## Author
[Yerofey S.](https://github.com/yerofey)

## License
[MIT](https://github.com/yerofey/cryptowallet-cli/blob/master/LICENSE)
