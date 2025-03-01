# Node Providers

### Default RPC Providers

Default RPC Providers we use. When Anti-MEV is switched off, public providers are used.

You can set your own Custom RPC: [RPC Management](../core-features/rpc-management.md)\
\
**Note:** We are constantly updating this so it may not be up to date, you can check through bot.

| Blockchain                    | Anti-MEV Provider                                          | Public Provider                                           |
| ----------------------------- | ---------------------------------------------------------- | --------------------------------------------------------- |
| **Sui**                       | `Fullnode *`                                               | `Fullnode`                                                |
| **Solana (SOL)**              | <p><code>Quicknode</code> <br>(Through Jito Bundles)</p>   | `Quicknode`                                               |
| **Ethereum (ETH)**            | `Mevblocker`                                               | `Alchemy`                                                 |
| **Ton (TON)**                 | `In House *`                                               | `In House`                                                |
| **Cronos (CRO)**              | `dRPC *`                                                   | `dRPC`                                                    |
| **Avalanche (AVAX)**          | `Publicnode*`                                              | `Publicnode`                                              |
| **BASE (BASE)**               | `Quicknode *`                                              | `Quicknode`                                               |
| **Binance Smart Chain (BNB)** | `Publicnode *`                                             | `Quicknode`                                               |
| **Arbitrum (ARB)**            | `Alchemy *`                                                | <p><code>Publicnode</code><br><code>Quicknode</code> </p> |
| **PulseChain (PLS)**          | `Publicnode` \*                                            | `Publicnode`                                              |
| **Optimism (OP)**             | <p><code>Alchemy</code></p><p><code>Publicnode</code>*</p> | `https://opt-mainnet.g.alchemy.com`                       |
| **Matic/Polygon (MATIC)**     | `Publicnode` \*                                            | `Publicnode`                                              |
| **Metis (METIS)**             | `Andromeda*`                                               | <p><code>Nodies</code><br><code>Andromeda</code></p>      |
| **Manta (MANTA)**             | `https://pacific-rpc.manta.network/http` \*                | `https://pacific-rpc.manta.network/http`                  |
| **Zetachain (ZETA)**          | `Blockpi *`                                                | `blockpi`                                                 |
| **Blast (BLAST)**             | `Blockpi *`                                                | `Blockpi`                                                 |

\* **Anti Mev Not Supported** [**(Set Your Own Antimev Custom Rpc)**](../core-features/rpc-management.md)

### Testnet

| Blockchain               | Anti-MEV Provider | Public Provider |
| ------------------------ | ----------------- | --------------- |
| **Avax Testnet (AVAXT)** | `Publicnode`      | `Publicnode`    |
| **BSC Testnet (BNBT)**   | `Publicnode`      | `Publicnode`    |

### Testnet (Deprecated)

| Blockchain                  | Anti-MEV Provider | Public Provider |
| --------------------------- | ----------------- | --------------- |
| **Arb Testnet (ARBT)**      | `Publicnode`      | `Publicnode`    |
| **Pulse Testnet (PLST)**    | `Publicnode`      | `Publicnode`    |
| **Matic Testnet (MATIC)**   | `Nodies`          | `Nodies`        |
| **Ethereum Testnet (ETHT)** | `Publicnode`      | `Publicnode`    |

