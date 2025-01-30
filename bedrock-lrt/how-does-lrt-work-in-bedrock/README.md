# 📑 How does LRT work in Bedrock

{% hint style="success" %}
uniETH is a LRT token on EigenLayer, with relatively matured system flow and restaking service live in mainnet, so uniETH is used to explain the high level architecture of Bedrock
{% endhint %}

Ethereum holders stand to enjoy sustainable and increasingly diverse yield opportunities by safeguarding the Ethereum network and leveraging the enhanced yield enabled by [restaking](../../eigenlayer/introduction-to-eigenlayer/restaking/).

We will initially enable a **secure LRT protocol** supporting native restaking, known as [uniETH](../../multi-asset-liquid-staking/unieth/). ETH is natively staked and restaked via Eigenpod, treating it as an external manager with the Eigenpod address controlled by the [Bedrock staking contract.](../../security/smart-contracts/)&#x20;

This design is **future-proof**, allowing for contract upgrades to accommodate future restaking delegation. The [modular design](modular-key-functions.md) enables us to implement the best strategies for operator delegation and [AVS](https://docs.eigenlayer.xyz/avs-guides/avs-developer-guide) selection, equivalent to choosing the optimal yield opportunities across AVS and selecting the best validator sets. With over three years of ETH native staking experience and a [battle-tested](../../security/battle-tested-protocol.md) Bedrock contract, we aim provide the best security and experience for our users.

Once the cap on liquid restaking is lifted, we will enable a vault accepting ETH and other LSTs, deploying them through EigenLayer on respective routes and leveraging the restaking delegation module for additional yield. Therefore, the Bedrock protocol becomes an **one-stop solution** for ETH holders to generate long-term yield.

uniETH undergoes an upgrade from an LST to LRT after one year, continuously providing high yield to uniETH holders.

\
