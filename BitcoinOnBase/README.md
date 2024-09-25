# Bitcoin On Base Data Dashboard

Welcome to the Bitcoin On Base data dashboard docs! This dashboard provides real-time insights and analytics on BTC activity on Base.

View the dashboard here

### https://base.bitcoinlayers.org

Base in not a bitcoin layer, so we don't cover it on https://bitcoinlayers.org. However, you can learn more about Base from L2Beat here

### https://l2beat.com/scaling/projects/base

## Onchain Information

Base RPC - https://base-mainnet.g.alchemy.com/v2/{API_KEY}

BTC tokens covered:

- **cbBTC**: Coinbase's cbBTC
- **tBTC**: Threshold's tBTC
- **axlBTC**: Axelar's axlBTC
- **dlcBTC**: DLCLink's dlcBTC

### cbBTC

Base token address - https://basescan.org/token/0xcbb7c0000ab88b473b1f5afd9ef808440eed33bf

### tBTC

Base token address - https://basescan.org/token/0x236aa50979d5f3de3bd1eeb40e81137f22ab794b

Ethereum's Base bridge address - https://etherscan.io/address/0x3154Cf16ccdb4C6d922629664174b904d80F2C35

Ethereum token address - https://etherscan.io/token/0x18084fba666a33d37592fa2633fd49a74dd93a88

### axlBTC

Base token address - https://basescan.org/token/0x1a35ee4640b0a3b87705b0a4b45d227ba60ca2ad

### dlcBTC

Base token address - https://basescan.org/token/0x12418783e860997eb99e8aCf682DF952F721cF62

## Metrics and Heuristics

All metrics are gathered through the lens of the aforementioned BTC assets. The two highest-signal metrics here for inter-network comparisons are Total Value Locked and Transaction Fees. Transactions, Active Addresses, and Holders are more useful for intra-network analysis.

- **Total Value Locked**: the total supply of a bridged-BTC token
- **Transactions**: all transactions that involve a given token
- **Transaction Fees**: the sum of fees from transactions involving a given token
- **Active Addresses**: the number of addresses involved in a transaction with a given token
- **Holders**: the number of addresses that hold a given token

### Total Value Locked

Bitcoin layers exist for several purposes. One of the most important reasons is to create more expressive environments for BTC the asset. Because of this, total value locked of BTC, or BTC locked, is an important metric to track. This represents not only BTC liquidity but also the willingness of users to lock up their BTC on bitcoin to use bridged versions on the layer.

### Transactions

Transactions is an easily-sybilled metric in low-fee environments. However, this dashboard exists for intra-network comparisons, which makes the metric more valuable. It's worth seeing the transaction dominance breakdown between various BTC assets, as well as their trends over time. Another reason to be wary of inter-network comparisons for transactions, or TPS, is that not every VM defines a transaction in the same way.

### Transaction Fees

While transactions themselves can be easily sybilled, fees are the bottleneck. Fees, aka revenue, are more representative of actual demand for blockspace as real money has to be paid. This is a higher signal metric than general transactions when comparing inter-network.

### Active Addresses

Like transactions, active addresses can be easily sybilled, but still provide signal for intra-network analysis.

### Holders

It is important to not confuse accounts with real users. This metric is easily sybilled.

## Contact

For any questions or feedback, please open an issue or contact us on socials

- Twitter https://x.com/BitcoinLayers
- Telegram https://t.me/+8rv-1I2gkmQ4ZmJh
