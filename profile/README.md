# Satay Finance

Satay Finance is an all-in-one DeFi portfolio management tool offering three interconnected products:

1. **Blocks** - composable DeFi primitive operations through trusted third-party protocols
2. **Strategies** - compositions of Blocks that facilitate multi-protocol yield generation
3. **Vaults** - secure capital pools that optimize allocations to Blocks and Strategies to maximize yield

# Blocks

[Satay Blocks](https://github.com/satay-protocol/satay-blocks) are wrappers for primitive DeFi operations. Blocks facilitate the creation of compound, multi-protocol yield strategies.

# Strategies

Satay Strategies are compositions of Blocks that enable complex yield generation in one click. Users can deposit into Strategies directly or indirectly through Vaults. The following Strategies are currently in development:

- [Leveraged Liquid Staking - Aries x Tortuga](https://github.com/satay-protocol/tortuga-aries-LLS)
- [LSD LP Farming - Ditto x Liquidswap](https://github.com/satay-protocol/ditto-farming)
- [Boosted LP Farming - Liquidswap](https://github.com/satay-protocol/liquidswap-automated-harvest-strategy)
- Standard Liquid Staking - [Ditto](https://github.com/satay-protocol/simple-ditto-strategy) / [Tortuga](https://github.com/satay-protocol/simple-tortuga-strategy)

# Vaults

[Satay Vaults](https://github.com/satay-protocol/satay-aptos) are secure capital pools that optimize allocations to Strategies to maximize yield while limiting risk. Users can deposit into Vaults for seamless, broad exposure to the Aptos DeFi ecosystem. 

# dApp

The Satay web app is available at this [link](https://app.satay.finance/) and its source is available in the [satay-client](https://github.com/satay-protocol/satay-client) repository.

![app.satay.finance_.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/fa40178c-c45b-4b70-9040-23246cd0a996/app.satay.finance_.png)

# Audit

The Satay Vault Architecture passed an audit by Halborn Security on January 6th, 2023. The report is available in [smart-contract-audit](https://github.com/satay-protocol/smart-contract-audit) repository.