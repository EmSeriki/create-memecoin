# Create Meme Coin on Algorand

## Task 1: Create Wallet and ASA

### Create Wallet

You need a new wallet to hold your Algorand. 

1. Get the Pera Algo Wallet app from Apple’s [App Store](https://apps.apple.com/us/app/pera-algo-wallet/id1459898525) for iOS devices or Google’s [Play Store](https://play.google.com/store/apps/details?id=com.algorand.android&hl=en&gl=US) for Android smartphones. Or you can use the [web version](https://web.perawallet.app/) of the wallet. 

   <img width="689" alt="pera-wallet-app-store" src="https://github.com/EmSeriki/create-memecoin/assets/82876072/ae055b6f-36da-4df4-8117-8e615b3d7cba">

2. Create a new wallet in the Pera app. 

3. Send 20 ALGO (roughly $4 currently) to the new wallet. 

### Create ASA

A memecoin on Algorand is an ASA (Algorand Standard Asset).

1. Go to https://app.dappflow.org/dashboard/home/

2. Click **Connect Wallet**. 

   ![dappflow-connect-wallet](https://github.com/EmSeriki/create-memecoin/assets/82876072/6553a7d8-ed2e-4003-ae12-53d658c15b3e)

3. On the Pera app on your smartphone: go through the menu icon > **Scan QR Code**. 

   ![pera-wallet-menu](https://github.com/EmSeriki/create-memecoin/assets/82876072/83fd12df-f321-4ee8-937b-8377c1ab4a05)

4. Scan the QR code on the Dappflow page to add your Pera wallet. 

5. From the Dappflow menu, click **Asset manager** and then **Create asset**. 

6. Fill in the details for your asset (meme coin). 

   <img width="624" alt="create-asa-details" src="https://github.com/EmSeriki/create-memecoin/assets/82876072/bd97a876-bafc-4626-b526-c32d50aa0f79">

7. Click **Create**. 

   **Note** that the operation will cost you 1 ALGO. 

8. Confirm the transaction from your Pera wallet. 

## Task 2: Provide Liquidity 

To allow people to trade something for your coin, you need to provide some liquidity first.

1. Go to https://app.tinyman.org

2. Connect your wallet.

3. Click the **Pool** tab. Click **Create a pool.**

4. Click **Select an asset** and deselect the **Verified only** checkbox.

   <img width="1143" alt="tinyman-pool-tab" src="https://github.com/EmSeriki/create-memecoin/assets/82876072/f61ff477-2847-4c30-ae46-4b0ef47835f5">

5. Enter your token name and select it.

   In our case, we entered “strongmoonai”.

6. Click **CREATE THIS POOL.** Confirm the operation from your Pera wallet. 

7. Add as much ALGO and ASA as you want.

   In our case, to test things out, we added a small amount (roughly a dollar worth of ALGO).

   <img width="880" alt="add-liquidity-tinyman" src="https://github.com/EmSeriki/create-memecoin/assets/82876072/fc17f8c1-08f8-44b9-a8f2-42d75b461596">

8. Click **ADD INITIAL LIQUIDITY**.

9. Click **CONFIRM**. Confirm the transactions from your Pera wallet. 

10. Click **GO TO POOL DETAIL** to view more information about the pool. 

Your meme coin should have some value now. After 30 minutes or thereabouts, your token will be listed on most ASA trackers and liquidity pools across the Algorand ecosystem. You can head to [Vestige.fi](https://vestige.fi/) (formerly TinyChart) to confirm things. 

<img width="1332" alt="strongmoonai-vestige" src="https://github.com/EmSeriki/create-memecoin/assets/82876072/b0d6ff64-8287-4b63-bf7e-943d7501b601">

As you can see, our coin now has some value. 

## Task 3: Add Logo and Lock Liquidity for Credibility

### Add Logo

Follow the instructions [here](https://github.com/tinymanorg/asa-list?tab=readme-ov-file#adding-your-icon) and create a pull request. 

### Lock Liquidity

Use [Tinylock](https://github.com/tinylock-org?tab=repositories) to lock some of the liquidity. When you lock the liquidity you provided, potential buyers become less likely to worry that you are going to steal all the liquidity or do a rugpull. 

Save the details of the smart contract for the liquidity lock and use it (alongside its link) as proof that you have locked the liquidity. 

Cheers.
