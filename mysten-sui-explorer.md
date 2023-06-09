# Sui Explorer by Mysten Labs

[Sui Explorer](https://suiexplorer.com/) lets you view data about transactions and activity on the Sui network. Use Sui Explorer to:
 * View up-to-date information about the activity and metrics on the Sui network.
 * Look up, verify, and track your assets and contracts.
 * Utilize fast, reliable, and transparent debugging and auditing data to help identify and resolve issues.
 * Get go-to-definition support for all smart contracts, referred to as packages in Sui.
 * View the geographic locations of currently active Full nodes.
 * View details about current validators, including performance and staking rewards.

 See the [Sui Explorer README](https://github.com/MystenLabs/sui/tree/main/apps/explorer#readme) for instructions on how to run the Explorer locally.

 ## Sui Explorer main page

The main page displays information about network statistics, current gas price, epochs and checkpoints, transaction activity, popular packages, current gas price, and a partial list of validators on the network, sorted randomly.

The **Network TPS** block shows the current transactions per second (TPS) and peak TPS on the network over the previous 30 days.

The **Current Epoch** block shows the current epoch number, time remaining until the epoch ends, and the time and day when the epoch started. Click the box to view details about the epoch, such as the checkpoints, participating validators, rewards, and storage fund balance.

The **Reference Gas Price** block shows the current gas fee for transactions, and the average gas fee over the previous 7 epochs or 30 epochs based on the setting you choose. You can display the value in MIST or SUI.

The **On the Network** box shows total number of packages, transaction blocks, and objects on the network. This is a cumulative running total since network genesis.

The **Sui Nodes** map shows the geographic location of nodes on the three Sui networks, Mainnet, Testnet, and Devnet. Larger blue dots indicate a larger larger number of nodes in the region. Hover your cursor over a country to see the number of nodes in that country.

The **Transactions** table includes the following tabs:
* **Transaction Blocks** - shows the transactions on the network, with the most recent transaction first. Click on a value in the **Digest** or **Sender** columns to view details about them. Click **More Transaction Blocks** below the table to view all transactions on the network. You can choose the number of results per page using the drop-down in the bottom-right corner.
* **Epochs** - Shows a list of completed epochs and details about them, such as transaction blocks and stake rewards. Click on an epoch number to view more details about it, or click on a checkpoint number for details about it. Click **More Epochs** below the table to view all epochs.
* **Checkpoints** - Lists the checkpoints for the current epoch and details about them. Click a value in the **Digest** column to view details about it. 

The **Validators** table lists some of the validators on the network in random order. Click on a validator to view more details about that validator. Click **More Validators** at the below the table to view all current validators on the network.

The **Popular Packages** section shows the most frequently accessed packages on the network. You can choose to show data for the previous 3 days (3D), 7 days (7D), or 30 days (30D). Click a value in the **Modules** column to view details about the module, and click a value in the **Packages** column to view the associated package.

## Choose a network

When you open Sui Explorer, it displays the transactions for the Mainnet network by default. You can also use the Explorer to view data for Sui Devnet, Sui Testnet, a local network running in your environment, or a custom RPC endpoint URL. Use the drop-down menu at the top-right of the page to choose a different network.

## Initiate staking from Sui Explorer

You can initiate a stake request for a validator directly from the detail page for in Sui Explorer. Each validator detail page displays data to help you choose a validator that matches your objectives for staking. If you identify a validator you want to stake with, just click **Stake SUI** near the validator name in the top-left of the page. When you click the link, you wallet opens to the staking flow for the selected validator. To learn more about staking with Sui Wallet, see [Stake and Earn SUI](mysten-sui-wallet.md#stake-and-earn-sui).

## Find your transaction

You can search for the transactions using an address, object ID, or transaction ID. For example, you can search for your wallet address to confirm a transaction or view additional details about a transaction you’ve approved. See [Sui Wallet](https://github.com/MystenLabs/mysten-app-docs/blob/main/mysten-sui-wallet.md) to learn how to create a wallet.

**To search for a transaction made using Sui Wallet**
1. Open your Sui Wallet.
1. Click the clipboard icon to copy your wallet address.
1. Open the Sui Explorer.
1. In the search field, paste your wallet address and then press **Enter**.
1. Click the address displayed under the search field.

The Explorer displays the **Address** details page for your wallet address, including owned objects and transaction history. You should see the same transactions in Explorer that you see in your wallet history. Click on a transaction to view the details for it.
