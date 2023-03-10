# offchain-chains-registry

chains.json contains all Cardano networks (sidechains, subnets, L2s)


```json
[
    {
        "chain": "Milkomeda",
        "url": "https://milkomeda.com",
        "version": "1.0",
        "logo": "???",
        "vm": "EVM",
        "vmVersion": "???",
        "vmFlavour": "Hyperledger Besu",
        "vmFlavourUrl": "https://www.hyperledger.org/use/besu",
        "type": "Sidechain",
        "subtybe": "Endochain",
        "walletNetworkCompatibility": ["EVM"],
        "bridgeUrls": ["https://cardano-bridge.milkomeda.com/bridge", "https://app.blueshift.fi/#/bridge"],
        "explorerUrls": ["https://explorer-mainnet-cardano-evm.c1.milkomeda.com"],
        "dappUrls": ["https://milkomeda.com/dapp-store"],
        "documentationUrls": [],
        "rpcEndpoints": [],
        "consensus": "IBFT",
        "consensusVersion": "2.0",
        "currency": "ADA",
        "goal": "EVM compatibility for Cardano",
        "description": "Milkomeda delivers rollup technologies to leading Layer 1 ecosystems by offering the most popular smart contracting language, Solidity, while enhancing inter-blockchain interoperability, user experience, and developer traction all at the Layer 2 level.",
        "USPs": []
    },
    {
        "chain": "Shareslake",
        "url": "https://shareslake.com",
        "version": "1.0",
        "logo": "???",
        "vm": "UPLC",
        "vmVersion": "Alonzo",
        "type": "Sidechain",
        "subtybe": "Endochain",
        "walletNetworkCompatibility": ["UPLC"],
        "bridgeUrls": ["https://dashboard.shareslake.com"],
        "explorerUrls": [],
        "documentationUrls": [],
        "rpcEndpoints": [],
        "consensus": "OUROBOROS",
        "consensusVersion": "PRAOS",
        "currency": "RUSD",
        "goal": "Scale Cardano and support asset backed stable coins with predictable transaction fees (paid in RUSD)",
        "description": "The first native stablecoin on Cardano. Discover the power of USD payments in Cardano. The future starts with RUSD, a fiat-backed stablecoin.",
        "USPs": ["Fees paid in RUSD."]
    }
]
```
