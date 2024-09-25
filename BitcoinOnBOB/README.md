# Bitcoin On BOB Data Dashboard

Welcome to the Bitcoin On BOB data dashboard docs! This dashboard provides real-time insights and analytics on BTC activity on BOB network.

View the dashboard here

### https://bob.bitcoinlayers.org

Learn more about BOB here

### https://bitcoinlayers.org/layers/bob

## Onchain Information

BOB RPC - https://rpc.gobob.xyz/

BTC tokens covered:

- **tBTC**: Threshold's tBTC
- **WBTC**: BitGos' WBTC

### tBTC

BOB token address - https://explorer.gobob.xyz/token/0x03C7054BCB39f7b2e5B2c7AcB37583e32D70Cfa3

Ethereum's BOB bridge address - https://etherscan.io/address/0x3F6cE1b36e5120BBc59D0cFe8A5aC8b6464ac1f7

Ethereum token address - https://etherscan.io/address/0x18084fbA666a33d37592fA2633fD49a74DD93a88

### WBTC

BOB token address - https://explorer.gobob.xyz/token/0xBBa2eF945D523C4e2608C9E1214C2Cc64D4fc2e2

Ethereum's BOB bridge address - https://etherscan.io/address/0x3F6cE1b36e5120BBc59D0cFe8A5aC8b6464ac1f7

Ethereum token address - https://etherscan.io/address/0x2260FAC5E5542a773Aa44fBCfeDf7C193bc2C599

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
