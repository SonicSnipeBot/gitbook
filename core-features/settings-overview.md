# Settings Overview

### Settings Menu <a href="#main-menu" id="main-menu"></a>

The **Settings Menu** provides options for customising various settings within Sonic Snipe Bot.&#x20;

To access the settings menu, type `/settings` or select the **Settings** option when interacting with Sonic Snipe Bot.

**Settings Menu Options:**

1. [**Gas Limit**](settings-overview.md#gas-limit): Set the default gas limit for transactions.
2. [**Gas Price**](settings-overview.md#gas-price): Set the default gas price for transactions.
3. [**Set Slippage**](settings-overview.md#slippage): Set the default slippage value for transactions.
4. [**Switch Network**](settings-overview.md#select-network): Select the network for trading.
5. [**Select Dex**](settings-overview.md#select-custom-router): Select Dex or Change Router.
6. [**Select RPC**](settings-overview.md#select-custom-rpc): Manage RPC Settings (Toggle Anti-Mev Etc).
7. [**Set Tokens To Buy**](settings-overview.md#default-token-to-buy): Set Token Range To Buy
8. [**Set Currency (ETH/BNB/ARB) To Buy**](settings-overview.md#default-network-currency-to-buy): Set currency (ETH/BNB/ARB, etc) Range to Buy
9. [**Wallet Menu**](settings-overview.md#wallet-menu): Manage Wallets, Includes Add, delete, transfer etc.
10. [**Wallet Keys**](settings-overview.md#display-wallet-keys): View your Wallet Keys
11. [**Miscellaneous Menu**](settings-overview.md#view-misc): Miscellaneous Settings
12. [**Transaction Settings**: ](settings-overview.md#transaction-settings-1)Transaction Settings
13. [**Security Settings**](settings-overview.md#security-settings): Security Settings
14. [**Stats Overview**](settings-overview.md#stats-overview): See Your Trading Stats.
15. [**Gains**](settings-overview.md#view-gains): See Your Gains Stats
16. [**My Settings**](settings-overview.md#display-my-settings): View your current settings.
17. [**Reset Settings**](settings-overview.md#reset-settings): Reset all settings to their default values.
18. [**Transaction Fail Safe:** ](settings-overview.md#transaction-fail-safe)Prevent's Tx going through if mostly likely to fail

<figure><img src="../.gitbook/assets/Screenshot 2024-09-20 at 3.49.22 PM.png" alt="" width="375"><figcaption></figcaption></figure>

***

### Select Network <a href="#select-network" id="select-network"></a>

To select the network for trading, follow these steps:

1. Navigate to the settings menu.
2. Select the "Select Network" option.
3. Choose your desired network.

You can access the Network Menu using the quick panel by simply typing `/network`.

<figure><img src="../.gitbook/assets/Screenshot 2024-10-21 at 9.22.31 PM (1).png" alt="" width="375"><figcaption></figcaption></figure>

[Back to Top](settings-overview.md#main-menu)

***

### Set (Currency Range To Buy) <a href="#default-network-currency-to-buy" id="default-network-currency-to-buy"></a>

To set the default amount of currency (ETH/BNB/ARB, etc) to buy, follow these steps:

1. Navigate to the settings menu.
2. Select the "Default Network Currency To Buy" option.
3. Input the default amount of currency you would like to buy.

You can access this using the quick panel by simply typing `/price`.

One Step Action Also Supported, for example: `/price 1`

This will set your Default Currency Amount to 1.

<figure><img src="../.gitbook/assets/Screenshot 2024-06-06 at 12.47.37 PM.png" alt="" width="375"><figcaption></figcaption></figure>

[Back to Top](settings-overview.md#main-menu)

***

### Set Token Range To Buy <a href="#default-token-to-buy" id="default-token-to-buy"></a>

To set the default amount of tokens to buy, follow these steps:

1. Navigate to the settings menu.
2. Select the "Default Token To Buy" option.
3. Input the default amount of tokens you would like to buy.

You can access this using the quick panel by simply typing `/tokens`.

One Step Action Also Supported, for example: `/tokens 10000`

This will set your Default Token Amount to 10,000.

<figure><img src="../.gitbook/assets/Screenshot 2024-06-06 at 12.48.57 PM.png" alt="" width="375"><figcaption></figcaption></figure>

[Back to Top](settings-overview.md#main-menu)

***

### Accessing the Wallets Menu <a href="#wallet-menu" id="wallet-menu"></a>

Quick Access To Wallet Management [Wallet Management](wallet-management.md)

### Quick Access

* **Switch Network**: Change your connection to another network by following the guided steps after clicking **Switch Network**.
* **Single Snipe**: Initiate a quick trade with the **Single Snipe** option.
* **Select Contract**: Quickly select a contract by using the **Contract** button.

<figure><img src="../.gitbook/assets/walletManagementSonic (1).png" alt="" width="375"><figcaption></figcaption></figure>

[Back to Top](settings-overview.md#main-menu)

***

### Gas Limit <a href="#gas-limit" id="gas-limit"></a>

To enter the gas limit menu, follow these steps:

1. Navigate to the settings menu.
2. Select the "Gas Limit" option.

You can also access this using the quick panel by simply typing `/limit`.

**Gas Limit Menu has 3 Options**

1. **Auto Gas Limit** - This will attempt to automatically set the Gas Limit provided by the Website API (You can toggle this On and Off).
2. **Default Gas Limit** - When **Auto Gas Limit** is turned off, the **Default Gas Limit** will be used.\
   **Default Gas Limit** will also take effect when the **Estimated Gas Limit** cannot be calculated from the Rpc Provider.
3. **Leverage Gas Limit** - This is the amount on top of the **Auto Gas Limit** amount provided by the **Website Gas Limit** Calculation. This only applies if **Auto Gas Limit** is on.\
   This Also Applies if **Estimated Gas Limit**\* was used.

**Note** A World 🌎 Symbol Will Appear if the Website Api Was Used to Retrieve the Gas Limit.\
No world symbol means the Estimated Gas Was Calculated from the Rpc Provider.

Quick Configuration Also Supported, for example: `/limit 500000` \
(This will set your Default Gas Limit to 500,000.)

<figure><img src="../.gitbook/assets/Screenshot 2024-09-08 at 1.05.11 PM.png" alt="" width="375"><figcaption></figcaption></figure>

[Back to Top](settings-overview.md#main-menu)

***

### Gas Price <a href="#gas-price" id="gas-price"></a>

<figure><img src="../.gitbook/assets/Screenshot 2024-06-06 at 12.51.18 PM.png" alt="" width="375"><figcaption></figcaption></figure>

**To enter the Gas Price Menu, follow these steps:**

1. Navigate to the settings menu.
2. Select the "Gas Price" option.

You can also access this using the quick panel by simply typing `/gas`.

**Gas Price has 4 Dynamic Gas Price Options: Low, Medium, High, Instant (Available on compatible EVM networks)**

*   **Low, Medium, High, and Instant** - These options are dynamically updated and fetched from the Website API and Rpc Provider, this will be used when you trade based on your selection.

    _Example_: If you select "High," your Dynamic Gas will always be on the high setting.
*   **Tip option** - This allows you to add a tip for miners. Tipping can potentially prioritise your transaction, especially during times of network congestion.

    \
    &#xNAN;_**How to use Tip Option**_**:**

    After selecting the "Gas Price" option:

    1. You will see a "Tip" button, depicted by a rocket emoji.
    2. Click on the "Tip" button to specify the amount you wish to tip.
    3. Enter the amount for the tip, which will be added to the gas fee of your transaction.

    **Quick Tip Shortcut**: To quickly access the tip option, use the command `/tip` or `/tip [number]` to directly enter a specific tip amount.

**Custom option** - If you select this, **Dynamic Gas** is turned off and your **Custom Gas Price** will be used.

**Max Option** - To avoid overpaying for gas, set a **Max Gas**. If the gas exceeds this number, the transaction won't go through.

_**Max Option Example**_: If the **Instant Dynamic Gas** is 150 but your **Max Gas** is 120, the transaction is prevented, saving money on a potentially expensive trade.

**One-Step Action supported:** for example, `/gas 20` sets your Default Gas Price to 20.

[Back to Top](settings-overview.md#main-menu)

***

### Set Slippage <a href="#slippage" id="slippage"></a>

**To enter the Slippage Menu, follow these steps:**

1. Navigate to the settings menu.
2. Select the "Slippage" option.

You can also access this using the quick panel by simply typing `/slippage`.

**The Tax Menu has 4 Options:**

1. **Auto Slippage** - The provided Buy/Sell Slippage from the Website API will be used. (Auto Slippage can be toggled On and Off).
2. **Default Slippage** - When **Auto Slippage is off** Or **When the Website API fails to get Auto Slippage**, Default Slippage is used.
3. **Leverage Slippage** - This is the slippage on top of the Website API Buy/Sell Slippage.
4. **Maximum Slippage** - Maximum slippage is used as a fail-safe for Auto Slippage. If Auto Buy/Sell Slippage is higher than Maximum Tax, the transaction will fail.

**Leverage Slippage Example**\
The token we want to buy has a Slippage of 10%, if we use 10% Slippage the transaction may fail, so we add **Leverage Slippage**. \
By default Sonic Sets Leverage Slippage to 2%, so the total Slippage to Use would be 12%, this prevents transaction Failure.

**Maximum Slippage Example**\
Someone launches a coin and sets slippage to 80%, my Maximum Slippage is set at 20%. \
I put through a trade of $500, this saves you 80% loss of funds of your $500 as you now prevented the transaction from going through through your Maximum Slippage set at 20%.

**Note** A World 🌎 Symbol Will Appear if the Website Api Was Used to Retrieve the Slippage Price. No world symbol means the Default Slippage Was Used.

One Step Action Also Supported, for example: `/slippage 10` (This will set Default Slippage to 10.)

**Note:** If you enter 0 or 100 there is **"No Slippage" (Not Recommended for MEV Bots)**

<figure><img src="../.gitbook/assets/Screenshot 2024-10-23 at 10.04.17 PM.png" alt="" width="375"><figcaption></figcaption></figure>

[Back to Top](settings-overview.md#main-menu)

***

### RPC Menu <a href="#select-custom-rpc" id="select-custom-rpc"></a>

Quick Access To [RPC Management](rpc-management.md)

[Back to Top](settings-overview.md#main-menu)

***

### Select Dex <a href="#select-custom-router" id="select-custom-router"></a>

**To access the Select Dex Menu, follow these steps:**

1. Navigate to the settings menu.
2. Select the Select Dex option.

This will show you which Dex is selected, on the rare case that you want to route your funds to a supported Dex's that allow i&#x74;**,** you can choose another Dex, **we do not recommend doing this unless you know what you are doing**.\
\
**An example would be:**\
On Solana, I want to route my buy through the JupiterSwap Router instead of Raydium.\
\
If you do not see a Dex supported please send us a message through our Community Chat, we Regularly add to the [**supported Dex's**](../sonic-essentials/supported-dexs.md).

You can also Access Select Dex by typing /dex

<figure><img src="../.gitbook/assets/Screenshot 2024-06-06 at 12.52.14 PM.png" alt="" width="375"><figcaption></figcaption></figure>

[Back to Top](settings-overview.md#main-menu)

***

### Stats Overview

To view your trading stats, navigate to the settings menu and select the **"Stats"** option. The stats page provides a detailed breakdown of your entire trading activity, including:\
\
Quick access to Stats using the command `/stats`

* **Total Traded Amount (USD):** Displays the total value of all trades across different networks.
* **Total Transactions:** The number of trades made on all networks.
* **Account Type:** Different account types determine the fees you pay. For example, a **Premium** account, which can be activated using `/premium`, means you do not pay any trading fees (at this point in time).
* **Amount Owed & Fees Paid:** Shows any outstanding fees or fees you've already paid.
* **First & Last Trade Dates:** Displays the date of your first trade and the most recent trade.

**Mainnet Stats**

For each network, the following information is shown:

* **Total Volume Traded (USD)**: The value of assets traded on the network.
* **Total Transactions:** The number of transactions made on the network.

Example breakdown:

* **BNB:** $361.39 | 25 Transactions
* **PLS:** $27.81 | 4 Transactions
* **ETH:** $2024.58 | 13 Transactions
* **SOL:** $42875.52 | 662 Transactions ... (And so on for other networks)

**Testnet Stats**

Testnet stats are shown separately and are not included in the overall total.

#### Account Types & Fees

Currently, users with **Premium** accounts do not pay any fees. Make sure to activate your premium account using the `/premium` command.

You can also view this information on the `/leaderboard` for rankings in our main chat portal.

<figure><img src="../.gitbook/assets/Screenshot 2024-10-23 at 10.06.49 PM.png" alt="" width="375"><figcaption></figcaption></figure>

[Back to Top](settings-overview.md#main-menu)

***

### View Your Gains <a href="#view-gains" id="view-gains"></a>

View Your Personal Gains for time periods of 24 hours, 7 days, 30 days & All Time Stats

Your gains may be featured in Public Gains, found in our Sonic Chat Group.

Quick Access `/gains`

<figure><img src="../.gitbook/assets/Screenshot 2024-06-06 at 12.53.07 PM.png" alt="" width="368"><figcaption></figcaption></figure>

[Back to Top](settings-overview.md#main-menu)

***

### View Your Purchases <a href="#view-gains" id="view-gains"></a>

View Your Purchases for time periods of 24 hours, 7 days, 30 days & All Time Stats

Your Purchases may be featured in Public Purchase Board, found in our Sonic Apes Group.

Quick Access `/buys`

<figure><img src="../.gitbook/assets/Screenshot 2024-06-06 at 12.54.44 PM.png" alt="" width="375"><figcaption></figcaption></figure>

[Back to Top](settings-overview.md#main-menu)

***

### Wallet keys <a href="#display-wallet-keys" id="display-wallet-keys"></a>

To view your private keys:

1. Navigate to the settings menu.
2. Select the "My Keys" option.
3. Enter your password that you entered when you configured the snipe bot.

**Note:** If you've forgotten your password, you will not have access to the private keys. You have to delete all wallets and re-configure the snipe bot.

**Note:** If you didn't set a password on startup, you will not need to enter a password. It is important to set a password on startup as it protects your Wallet Keys. If someone has access to your telegram accounts, they can easily access your keys if you don't set a password.

<figure><img src="../.gitbook/assets/walletKeysSonic (1).png" alt="" width="375"><figcaption></figcaption></figure>

[Back to Top](settings-overview.md#main-menu)

***

### Miscellaneous Menu <a href="#view-misc" id="view-misc"></a>

The Miscellaneous Menu provides a variety of settings that allow users to customize their experience, manage notification preferences, adjust privacy settings, and fine-tune the application's behavior to suit individual needs.

To Access Transaction Settings Go To /settings Menu

You can also access this using the quick panel by simply typing `/misc`.

<figure><img src="../.gitbook/assets/Screenshot 2024-06-06 at 1.00.00 PM (1).png" alt="" width="366"><figcaption></figcaption></figure>

**Notifications**

* **Turn on Notifications on Purchase**\
  Toggle Notifications of Gains/Loss's

#### User Interface

* **Display Wallet on Snipe Menu**\
  Toggle the visibility of your wallet on the Snipe Menu for privacy.\
  You can also do this with `/more` to show wallet and `/less` to hide wallet

#### Dex Interaction

* **Auto Switch Dex on Higher LP Pool**\
  Automatically switches to a Dex with a higher liquidity pool for better trading conditions.

#### Gains and Reporting

* **Reset Gains (%) for Wallet on Current CA**\
  Resets the displayed gains for the wallet on the current contract address. You can also access this using the quick panel by simply typing `/resetgains`.

#### Remove All Contracts

* **Remove all Contracts For Network** This Will remove all contracts for Current Network.

#### Privacy and Customisation

* **Change Alias**\
  Customise your alias used in the application for increased privacy.

#### Language

* **Change Language**\
  We Support a Variety of Languages such as Chinese, Japanese & Korean. Use /language for quick access

[Back to Top](settings-overview.md#main-menu)

***

### Security Settings <a href="#security-settings" id="security-settings"></a>

<figure><img src="../.gitbook/assets/Screenshot 2024-10-23 at 9.13.12 PM.png" alt="" width="375"><figcaption></figcaption></figure>

The **Security Settings** can be accessed from the `/settings` menu. Additionally, you can access it from the Snipe menu or by typing `/security`.

The Security Settings menu offers several options to enhance the security of your account within the Sonic Snipe Bot:

#### **🔑 Set Password**

Setting a password is a fundamental step in securing your account. This ensures that only you can access your account and its features.

**Benefits of Setting a Password:**

* 🛡️ Protects your account from unauthorised access.
* 💰 Enables wallet and bridge transfers.
* 🔒 Allows you to lock your account, preventing trading activities while you're away.

**Recommendation:**\
When you first create an account, you’ll be prompted to set a password. If you haven’t done so yet, we **strongly recommend** setting one to ensure your account's security.

***

#### **📧 Set an Email**

Linking an email address to your account is important for account recovery. If you forget your password or need to verify your identity, your email will help us restore access to your account.

**Additional Security:**\
This extra layer of security ensures we can assist you in recovering access to your account if needed. 📩

***

#### **🔒 Lock/Unlock Your Account**

If you're not using your account for an extended period, consider locking it to prevent any unauthorized activity. Locking your account ensures no trades or other sensitive activities take place while you're away.

**Features of Account Lock:**

* 🚫 Prevents trading, limit trading, and sniping new launches.
* 🔄 Existing limit trades and snipes will continue running, even if your account is locked.

**Unlocking Your Account:**\
To resume trading and regain access to all features, simply unlock your account from the security settings. 🔓

***

#### **🏷️ Set an Alias**

Setting an alias personalises your presence within the Sonic Snipe Bot platform. Your alias is used for identification in the leaderboard and community updates.

**Why Set an Alias?**

* 🌟 **Public Recognition:** Your alias will help others identify you when your trades or purchases are highlighted for VIP members.
* 👤 **Maintain Privacy:** If you prefer to stay anonymous, you can choose an alias that doesn't directly identify you, or set your alias as “anon.”
* 🤝 **Increased Engagement:** A recognisable alias fosters engagement within the community, allowing others to see your activity and contributions.

**How to Set an Alias:**\
Click on **Set an Alias** or type **/alias**. A prompt will appear where you can either:

* ✍️ Type your username to use it as your alias.
* 🕵️‍♂️ Type “anon” to remain anonymous.

Once set, your alias will be displayed in your next trade and within community updates. 🌐

***

### Transaction Settings <a href="#transaction-settings" id="transaction-settings"></a>

The Transaction Settings allow users to manage their trading operations with options to simulate trades, set auto approvals, and manage risk settings.

To Access Transaction Settings Go To /settings Menu, Click 'Misc', 'Transaction Settings'

You can also access this using the quick panel by simply typing `/tx`.

<figure><img src="../.gitbook/assets/Screenshot 2024-06-06 at 12.58.38 PM (1).png" alt="" width="375"><figcaption></figcaption></figure>

#### Testing

* **Test Transactions**\
  Enables simulated transactions for testing purposes without executing real trades.\
  You can also toggle this option with `/sonic`

#### Transaction Safety

* **Skip Fail Safe**\
  Disables the fail-safe mechanism to prevent stopping transactions that are likely to fail.\
  [Read More ](settings-overview.md#transaction-fail-safe)

#### Approval Settings

* **Auto Approve Max on Buy**\
  Automatically grants maximum token spending approval to ease the buy process.
* **Revoke After Sell (On Approve Max)**\
  Removes token spending approval from the router after a sale is completed.

#### Incentives

* **Miner Tipping For Approval Tx's**\
  Incentivise miners with a tip to prioritise your approval transactions.

#### Wallet Balance Check

* **Check Wallet Balance Before Sending Tx**\
  Toggle Check if you have enough funds to do the tx before sending.

[Back to Top](settings-overview.md#main-menu)

***

### My Settings <a href="#display-my-settings" id="display-my-settings"></a>

To view your current settings, follow these steps:

1. Navigate to the settings menu.
2. Select the "My Settings" option.
3. The bot will display all the settings you have set.

You can also access this by simply typing `/config`.

<figure><img src="../.gitbook/assets/Screenshot 2024-09-08 at 12.58.30 PM (1).png" alt="" width="375"><figcaption></figcaption></figure>

[Back to Top](settings-overview.md#main-menu)

***

### Reset Settings <a href="#reset-settings" id="reset-settings"></a>

<figure><img src="../.gitbook/assets/Screenshot 2024-06-06 at 1.04.21 PM.png" alt="" width="375"><figcaption></figcaption></figure>

#### To revert all settings to their default states, follow these steps:

1. Navigate to the settings menu.
2. Choose the Type of Settings to Reset.

#### Types of Resets:

*   **Reset Main Settings:** This reverts your primary Settings across all networks. This includes defaults such as selected contract when typing `/snipe`, gas, gas limit, slippage RPC, token price, currency price settings, etc.

    > **Note:** This action won't delete your contracts. To remove contracts for specific networks, navigate to `/contracts` and select the desired contracts to delete.
* **Reset Snipe Settings:** This focuses on snipe-related settings. Be aware that all active snipes will be halted and subsequently deleted.
* **Reset Limit Settings:** Resets all limit-specific settings. Important: All active limit trades, including monitored ones, will be stopped and deleted.
* **Reset Sonic Snipe Bot:** Removes everything, (all of the above) including private keys, vanilla start.

For quicker access, you can also use the command `/reset`.

[Back to Top](settings-overview.md#main-menu)

***

### Transaction Fail Safe

Sonic Snipe Bot Uses Transaction Fail Safe to Prevent Transactions from going through if they are most likely to fail.

This is on for all EVM networks except BASE which is not Supported.

The Transaction Will Attempt to Send and If its Likely to Fail it Will not Send the Transaction. This Will Save you on Gas Fees, Specifically for Eth where Transactions could cost from $20 -$200.

You Can Turn This Off, from the [Settings Menu](settings-overview.md), Located Under[ Misc ](settings-overview.md#view-misc)Click Skip Fail Safe.

<figure><img src="../.gitbook/assets/Screenshot 2024-06-06 at 1.07.21 PM.png" alt="" width="375"><figcaption></figcaption></figure>

### Quick Links

* [Home](../)
* [Getting Started](/broken/pages/WXbtUkA1oAkQRdqfRC00)
* [Single Wallet Snipe](single-wallet-snipe.md)
* [Multi Wallet Snipe](multi-wallet-snipe.md)
* [Snipe Liquidity](snipe-new-launches.md)
* [Limit Trading](limit-trading.md)
* [Settings](settings-overview.md)
* [Quick Panel](../sonic-essentials/quick-panel.md)
