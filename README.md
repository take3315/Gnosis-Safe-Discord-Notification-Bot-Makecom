# Gnosis-Safe-Notification-Bot-makecom

This is a BOT that monitors txn status of Gnosis SAFE and posts a Discord message notifying when the txn receives required number of confirmations (e.g. 6 confirmations in 6/10 safe).

SETUP
- Line 24: Replace with your 0x Safe address: https://safe-transaction-mainnet.safe.global/api/v1/safes/0x...(REPLACE HERE)/multisig-transactions/
- Line 514: Replace with your SAFE's required confirmation numbers (if 6-of-to then 6)
- Line 526: Replace with any msg you wish to post to Discord.
- Line 527: Replace with your Discord Webhook.

USE
- Import 'blueprint' into Make(https://www.make.com) as a scenario
  ![image](https://user-images.githubusercontent.com/94933955/177709146-ca5efdcc-9d29-425f-b565-bb1cf1089653.png)
- Set Scheduling interval to 60 mins.
