# 🔍 Introduction to Babylon

Babylon is a Bitcoin staking protocol which, when used in conjunction with an off-the-shelf consumer PoS chain, has three important security properties:

1. Fully slashabable PoS security. Whenever there is a safety violation, 1/3 of the Bitcoin stake is guaranteed to be slashed. As long as 2/3 of the Bitcoin stake follows the PoS protocol honestly, the PoS chain is live.
2. Staker security. Each Bitcoin staker is guaranteed to be able to withdraw its funds, or unbond, as long as the staker follows the PoS protocol honestly.
3. Staker liquidity. Unbonding of the staked bitcoins is guaranteed to be secure and fast without the need of social consensus.

### Babylon Bitcoin Staking <a href="#babylon-bitcoin-staking" id="babylon-bitcoin-staking"></a>

At its core, [Babylon](https://babylonchain.io/) addresses 2 critical needs of the cryptocurrency market:

* **Proof-of-Stake capital dependency:** The security of a PoS network depends on the value of the assets staked. Due to network effects, such capital can be hard to attract with projects usually adopting extremely high inflation rates to incentivize more capital through exaggerated staking yields. This hyper-incentivization is not only unsustainable but also diverts what are limited protocol funds away from building application use-cases on the chain. It is much easier and cheaper for smaller PoS chains to pay for borrowed economic security from an external established blockchain.
* **Proof-of-Work capital dormancy:** PoW blockchains, such as BTC, secures the network through utilizing computational power to solve complex mathematical puzzles. As such, BTC inflation is instead directed towards miners who have invested resources into mining hardware and infrastructure. Consequently, BTC holders do not benefit from any form of native yield generation as their assets are idle and not actively securing the network.&#x20;

In effect, **Babylon matches PoS chains that are willing to pay yield in exchange for security and BTC holders whose BTC is economically secure but does not generate yield**. By depositing (i.e. staking) BTC into a non-custodial vault which implements the PoS chain’s slashing rules, BTC stakers pledge the value of their staked BTC in exchange for yield from the PoS chain. Crucially, this process does not require third party services nor the transfer of BTC ownership hence retaining the security and decentralization aspects of Bitcoin.

Babylon has committed to [making the Bitcoin staking protocol open-sourced](https://docs.babylonchain.io/docs/introduction/babylon-overview) once the core primitives have been developed. You can view the full list of Babylon ecosystem integrations [here](https://babylonchain.io/ecosystem).
