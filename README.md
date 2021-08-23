# cryptowallet-cli

> Crypto wallet generator CLI tool

![Screenshot](https://i.imgur.com/fDXfWWK.png)

---

## Install
```bash
# via Yarn
$ yarn global add cryptowallet

# or via NPM
$ npm install --global cryptowallet
```

## Usage
```bash
# generate random ETH/BNB wallet
$ cryptowallet

# generate random ETH/BNB wallet with desired prefix
$ cryptowallet -p aaa

# generate random BTC wallet
$ cryptowallet -c BTC
```

## Cryptos supported
- `BTC` (Bitcoin)
- `ETH` (Ethereum) [prefix supported]
- `BNB` (Binance Coin - BEP20 BSC)  [prefix supported]
- `DOGE` (Dogecoin)
- `BCH` (Bitcoin Cash)
- `LTC` (Litecoin)
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
- Supports 22 cryptos
- Supports address prefix
- Works fully offline

## Author
[Yerofey S.](https://github.com/yerofey)

## License
This library licensed under [MIT](https://github.com/yerofey/cryptowallet-cli/blob/master/LICENSE).
