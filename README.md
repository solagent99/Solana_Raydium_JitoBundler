# Solana Raydium Jito Bundler

As solana raydium jito bundler, it designed to facilitate buying and selling with 27 wallets simultaneously on the Solana blockchain. It used cutting-edge technologies for solana bundler so it's wonderful for for users looking to manage multiple transactions efficiently and effectively. This is basic version for giving basic understanding solana bundler on raydium using jito, so for real product, you need to get advanced version. Feel free to reach out of me when you need advanced version(https://t.me/shinnyleo0912)




## Getting Started

To get started with the Solana Raydium Bundler, follow these steps to ensure a smooth setup and execution process.

### 1. How to run repository 

#### Clone my repository
Git clone https://github.com/solagent99/Solana_Raydium_JitoBundler.git

#### Edit the `.env` File
Before running the script, you need to configure the `.env` file. There are two keypairs required:

- **SOL Distribution Fees Keypair:** This keypair is used for paying all the SOL distribution fees.
- **Pool Creation Keypair:** This keypair is used for creating the pool. It is recommended that these keypairs have no ties to each other for security purposes.

You can use the same keypair for both if you are just testing the script. Make sure to store these keypairs securely.

### 2. Script Functions

**Important:** Follow the steps sequentially to ensure proper execution and avoid errors.

#### Create Keypairs (Step 1)
This step is crucial if you want to ensure that there is no SOL in the wallets. It is not necessary for every launch but is recommended for initial setups or resets.

#### Premarket (Step 2)
This is a multi-step process that needs to be done in a specific order:

1. **Execution Order:** Complete all steps from 2 to 6 in sequence.
2. **Bundle ID Check:** After each step, verify the Bundle ID to ensure it has landed correctly.
3. **Retry if Needed:** If the bundle does not land, increase the tip and retry. Exit if necessary.
4. **Verification:** Use the [Jito Block Explorer](https://explorer.jito.wtf/) to check if the bundle landed. Ignore the "Landed - no" indicator; instead, check if the first included transaction is confirmed.

#### Create Pool (Step 3)
Creating a pool might require multiple attempts:

- **Spam the Function:** If the pool creation does not land on the first try, spam the function.
- **Increase the Tip:** A tip of 0.1 SOL or more is recommended for better chances of landing within the first few tries.

#### Sell Features (Steps 4 and 5)
Once the pool is live, you have two options for selling:

1. **Sell All Keypairs at Once (Step 4):** Use this step to sell all keypairs simultaneously and reclaim WSOL in Step 7 of Premarket (Step 2) after rugging.
2. **Sell in Percentages (Step 5):** You can sell small percentages of the supply on demand. This involves sending a specified percentage of every keypair's token balance to the fee payers, then selling it all in one singular bundle on one wallet.

#### LP Remove (Step 6)
Removing LP is straightforward:

- **Non-Burn Removal:** If you do not burn your LP, it will simply be removed.

## Troubleshooting and Tips

- **Bundle Landing:** Ensure your bundle lands by adjusting the tip or retrying the process as needed. Use the Jito Block Explorer for verification.
- **Secure Keypairs:** Keep your keypairs secure and ensure they are correctly configured in the `.env` file.
- **Spam Wisely:** When spamming functions, monitor the transactions to avoid unnecessary SOL expenditure.

### Conclusion

The Solana Raydium Bundler is a robust tool for managing multiple transactions on the Solana blockchain. By following the setup and script functions outlined above, you can efficiently handle buying and selling operations with ease. 

Follow me on github and give star to this repository.
