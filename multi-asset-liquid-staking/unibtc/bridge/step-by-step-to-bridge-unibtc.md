---
icon: bridge-circle-check
---

# Step by step to bridge uniBTC

{% hint style="warning" %}
The bridge function is work in progress, please check [Bridge](./) for the supported networks first
{% endhint %}

1. Go to [https://app.bedrock.technology/unibtc](https://app.bedrock.technology/unibtc) page, connect wallet, then click Bridge tab.

<figure><img src="../../../.gitbook/assets/Screenshot 2024-11-22 at 6.40.34 PM.png" alt="" width="302"><figcaption><p>Bridge tab</p></figcaption></figure>

2. Fillup the form before submission

<figure><img src="../../../.gitbook/assets/Screenshot 2024-11-22 at 6.44.53 PM.png" alt="" width="303"><figcaption><p>Fillup form before submission</p></figcaption></figure>

3. Choose supported source chain and destination chain. You can also click the Swap button in the middle to switch the selected source and dest. chains.&#x20;
4. Enter amount of uniBTC to be bridged to the dest. chain.
   1. Click Max button to use the max available amount.
   2. Maximum amount must be less than the [quota](./).
   3. No minimum amount at the moment.
5. Additional info:
   1. The estimantion time varies in range of 5-20 minuntes depends on the network selected.&#x20;
   2. Fees: Fees are applied by the Chainlink CCIP protocol, with the amount determined by the network conditions.&#x20;
   3. User must grant sufficient allowance to Bedrock bridge contract before sending the funds.
   4. Token contract is the router contract done by Chainlink CCIP.
   5. Cross-chain History is provided by Chainlink CCIP per wallet address.
6. Grant the allowance by clicking Approve button, with sufficient amount to the token contract
7. Click Send button, user will see confiration popup window, and user needs to check:
   1. Amount of uniBTC to be transffered.
   2. Estimatied time.
   3. Fees charged by CCIP
8. User clicks the Confirm button, and sign in connnected wallet to trigger the token transfer

<figure><img src="../../../.gitbook/assets/Screenshot 2024-11-22 at 5.56.23 PM.png" alt="" width="375"><figcaption><p>Status popup window</p></figcaption></figure>

9. The status popup: the popup window shows the below info:
   1. Message ID: The Chainlink CCIP message ID used for the status of current bridge function.
   2. Source Transaction: The initial function triggered from source chain.
   3. Amount: the amount of uniBTC to be transffered to the destination chain.
   4. Source chain
   5. Desination chain



<figure><img src="../../../.gitbook/assets/Screenshot 2024-11-22 at 5.55.47 PM.png" alt="" width="375"><figcaption><p>Transfer success popup</p></figcaption></figure>

1. Transfer success popup: Upon transaction finality confirmation, it shows below info:
   1. Amount of transferred uniBTC.
   2. The source chain to destination chain.
   3. Close button to hide this popup window
