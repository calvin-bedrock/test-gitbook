# 🔐 Oracle-less

Bedrock chose to relying more extensively on on-chain data to compute its estimated validator balances and staking rewards, instead of using an oracle service that utilizes off-chain data and calculations.&#x20;

The main reason for why oracles are necessary is because ETH 2.0 does not differentiate withdrawal credential addresses so the oracle functions by running calculations off chain to tell the smart contract which part of received ETH tokens that are received are classified as full withdrawals, and not consensus rewards. The oracle also helps with accounting for pending validators, stopped validators, and slashed validators.&#x20;

In essence, utilizing oracles help with estimating the validator balance and rewards sum because there is no direct way to do it with ETH 2.0. It is worth noting that using oracles carry inherent risks such as its service being compromised or malicious actors getting access to it.&#x20;

This is a huge milestone for Bedrock as it has mitigated the risk of inaccurate off-chain calculations and the risk of potential compromises to the oracle service. Instead, Bedrock is able to get the native, on-chain reward and balance estimates for the validators that are deployed, thus ensuring a peace of mind for all our staking customers.&#x20;

Smart contract to verify uniETH Exchange Ratio (function 11): [https://etherscan.io/address/0x4beFa2aA9c305238AA3E0b5D17eB20C045269E9d#readProxyContract](https://etherscan.io/address/0x4beFa2aA9c305238AA3E0b5D17eB20C045269E9d#readProxyContract)



