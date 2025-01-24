# Snipe New Launches

### Snipe New Launch Menu <a href="#main-menu" id="main-menu"></a>

**Settings Menu Options:**

1. [**Access the Snipe New Launch Menu**](snipe-new-launches.md#access) : How To
2. [**Set (Currency Amount)**](snipe-new-launches.md#token-to-buy): Set the amount of tokens to Snipe.
3. [**Set (Token Amount)**](snipe-new-launches.md#currency-to-buy): Set the default amount of network currency (ETH/BNB/ARB) to Snipe.
4. [**Snipe On**](snipe-new-launches.md#snipe-on): Snipe on Contract Triggers
5. [**Attempts**](snipe-new-launches.md#attempts): Attempts to Snipe
6. [**Anti Rug**](snipe-new-launches.md#antirug): Anti Rug
7. [**Set Slippage**](snipe-new-launches.md#slippage): Set the default slippage value for transactions.
8. [**Gas Price**](snipe-new-launches.md#gas-price): Set the default gas price for transactions.
9. [**Gas Limit**](snipe-new-launches.md#gas-limit): Set the default gas limit for transactions.
10. [**Enable Snipe**](snipe-new-launches.md#enable): Enable / Disable The Snipe
11. [**Select Wallets**](snipe-new-launches.md#multi): Select Multiple Wallets to Snipe With
12. [**List/ Manage Your Snipe Orders**](snipe-new-launches.md#list): List/ Manage your Snipes

***

<figure><img src="../.gitbook/assets/Screenshot 2024-06-06 at 12.23.10 PM.png" alt="" width="375"><figcaption></figcaption></figure>

### How to Access the Snipe New Launch Menu <a href="#access" id="access"></a>

**Access the Snipe New Launch Menu**:

* Type `/newlaunch` in your chat window.
* Select `/newlaunch` from the Quick Panel.

**Alternatively**:

Go To the /Snipe Single Wallet Menu and click "Snipe New Launch"

***

### Set (Currency To Buy) <a href="#token-to-buy" id="token-to-buy"></a>

Set the amount of currency you want to snipe.

[Back to Top](snipe-new-launches.md#main-menu)

***

### Set Tokens To Buy <a href="#currency-to-buy" id="currency-to-buy"></a>

Set the amount of Tokens you want to snipe.

[Back to Top](snipe-new-launches.md#main-menu)

***

### Snipe On Feature <a href="#snipe-on" id="snipe-on"></a>

The **Snipe On** feature allows users to initiate a snipe based on specific contract events defined by the developer.

#### Usage

To use this feature, simply navigate to the **Snipe On** section and select the desired trigger event. For instance, if you aim to execute a snipe upon the occurrence of either "Open Trading" or "Enable Trading" events, you would activate the corresponding button, typically labeled as "openTrading".

#### Default Settings

By default, the feature is set with the following options:

* **💧 Liquidity ✅**: This option is pre-selected. Users have the choice to deselect it if they prefer to wait for other specific events like "Enable Trading" or "Open Trading".
* **📚 Functions ✅**: Also selected by default. Users can deselect this option if they wish to focus solely on liquidity events, or they may opt to deactivate both liquidity and functions to utilize the Anti Rug Feature exclusively.

> **Note:** Users are advised to carefully select triggers that maximize the chances of a successful snipe. Recommended options often include "Enable Trading" or "Open Trading".

<figure><img src="../.gitbook/assets/Screenshot 2024-06-06 at 12.23.43 PM.png" alt="" width="360"><figcaption></figcaption></figure>

[Back to Top](snipe-new-launches.md#main-menu)

***

### Anti Rug Feature <a href="#antirug" id="antirug"></a>

#### How Does Anti Rug Work?

The Anti Rug feature is designed to safeguard your investments by detecting and front-running malicious transactions initiated by developers. This preemptive action aims to sell your tokens before they are impacted by such transactions.

**Key Aspects:**

* **Activation Without Sniping:** Anti Rug can be enabled independently from the 'Snipe On' feature. To do so, deselect both the 'Liquidity' and 'Function' options under 'Snipe On'.
* **Recommended Usage:** This feature is particularly beneficial when holding a substantial volume of tokens. Be mindful of the potential high gas fees incurred due to the front-running process.
* **Multiple Wallets Support:** When enabled, Anti Rug attempts to simultaneously front-run and sell tokens across all configured wallets.

**Challenges and Limitations:**

While Anti Rug is a robust tool, it's important to recognize that its effectiveness can be impacted by various developer tactics. Developers may employ strategies like simulating liquidity removal to thwart sniping attempts. Additionally, it is not guaranteed that a front-run attempt will always be successful. Users should be aware of these potential limitations and exercise caution.

#### Identifying Malicious Transactions

Anti Rug primarily focuses on countering activities such as:

* Transactions triggering liquidity removal.
* Transactions involving token minting.
* Other malicious activity that is deemed harmful.

#### Activation Instructions

To enable the Anti Rug feature, tick the 'Anti Rug' checkbox in the settings. This option is typically enabled by default for user convenience.

> **Note:** Ensure your wallet is sufficiently funded to handle the potentially high gas costs associated with activating the Anti Rug feature.

[Back to Top](snipe-new-launches.md#main-menu)

***

### Set Slippage <a href="#slippage" id="slippage"></a>

Quick Access to the [Slippage](settings-overview.md#slippage) Menu

[Back to Top](snipe-new-launches.md#main-menu)

***

### Gas Price <a href="#gas-price" id="gas-price"></a>

Quick Access to the [Gas Price](settings-overview.md#gas-price) Menu

[Back to Top](snipe-new-launches.md#main-menu)

***

### Gas Limit <a href="#gas-limit" id="gas-limit"></a>

Quick Access to the [Gas Limit ](settings-overview.md#gas-limit)Menu

[Back to Top](snipe-new-launches.md#main-menu)

***

### Attempts to Snipe <a href="#attempts" id="attempts"></a>

The Attempt to Snipe Will be triggered for Each Snipe On.\
Enabled Event and also When Liquidity is Added, until the Snipe Has Gone Through Successfully.\
The Attempts Will Also be Triggered on Anti Rug.

**For Example:**

1. I Set my Attempt to Buy at 2.
2. I Enable My Snipe.\
   (a) Liquidity Is Added. Sonic Attempts to Snipe.\
   (b) 1st Attempt Fails.\
   (c) Sonic Attempts to Snipe on 2nd Attempt.\
   (d) Snipe Fails.
3. (a) Open Trading is Executed, and in my Snipe On I have Open Trading Enabled.\
   (b) Sonic Attempts to Snipe, Fails.\
   (c) Sonic Attempts to Snipe Again, Snipe is a Success!

[Back to Top](snipe-new-launches.md#main-menu)

***

### Enable Snipe <a href="#enable" id="enable"></a>

Before you Enable your Snipe, Make Sure you Configured Your Snipe Settings Properly. We Recommend you Enable Some **Snipe On** Triggers, Though you dont have to, Sonic Will Attempt to Snipe on Liquidity Add, But if you want a higher Success Rate We Strongly Recommend To.

When you are Ready , Click the "Disabled ❌"

**Note** Snipe's Have An Expiry of 30 mins, so make sure you enable this only when the token is about to go Live. We Will increase this Timeframe In the Future as we Invest in Nodes / Node Hosting, most likely when Sonic Goes Live.

[Back to Top](snipe-new-launches.md#main-menu)

***

### Select Wallets to Snipe <a href="#multi" id="multi"></a>

<figure><img src="../.gitbook/assets/Screenshot 2024-08-06 at 12.39.08 PM (2).png" alt="" width="348"><figcaption></figcaption></figure>

In Beta Testing, You will find that your selected wallet is already checked. If no Wallets are checked your selected Wallet will be checked.

Choosing Multiple Wallets Will allow you to Snipe With Multiple Wallets.

You will also Notice, Your Wallet Balance's You Selected are shown, including how much tokens you are currently holding. This should be 0 as you haven't "Sniped" the token. It will give you a rough idea if you have enough funds for sniping in other wallets, quickly.

[Back to Top](snipe-new-launches.md#main-menu)

***

### List Your Snipe Orders <a href="#list" id="list"></a>

Sonic Allows Multiple Snipes at the Same Time. This means you can simultaneously Snipe Multiple Contracts on Different Networks at the Same Time. Not only that, you can snipe multiple wallets of a contract at the same time.

To List your Snipes Type `/neworders`

To Disable a Snipe Simply Click The Token Name With the ✅

<figure><img src="../.gitbook/assets/Screenshot 2024-06-06 at 12.27.13 PM.png" alt="" width="375"><figcaption></figcaption></figure>

[Back to Top](snipe-new-launches.md#main-menu)

***

### Quick Links

* [Home](../)
* [Getting Started](broken-reference)
* [Single Wallet Snipe](single-wallet-snipe.md)
* [Multi Wallet Snipe](multi-wallet-snipe.md)
* [Snipe New Launches](snipe-new-launches.md)
* [Limit Trading](limit-trading.md)
* [Settings](settings-overview.md)
