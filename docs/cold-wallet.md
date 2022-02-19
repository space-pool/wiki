# Cold wallet

A cold wallet is very useful when you want to protect your precious xchs.
You should assume that you main node/farmer is under constant atack because is facing internet 24x7.
Having your xchs in the main node makes it easier for another person or software to steal it. 

## Create the cold wallet

You should create your cold wallet in a computer without internet.
The following steps will guide you through the process

1. Download the chia installer to an usb drive and copy it to the computer you will be creating your cold wallet
1. Connect the usb drive and copy and install the chia client
1. Create a new set of 24 words
1. Open your chia client (You don't need to sync your db or wallet db)
1. Go to the wallet tab and copy the receive address to a notepad (This is going to be your cold wallet)
1. Copy those 24 words to a secure place  (You could even print it in a paper and keep it very secure, maybe a bank box or a safe)
1. Delete the 24 words from the computer you installed chia
1. Uninstall chia and remove all the folders related (.chia folder created and the chia-blockchin folder)

## Farmer rewards

Close your app, go to your config.yaml, and replace in the 2 places you will find the **xch_target_address** with the new address 
you copied from the cold wallet and Start your chia app. An easier and secure way is just  go to the farm tab and change both addresses in 
the Farming rewards (Click in the 3 dots and click in Manage Farming Rewards)

## Pool rewards

In order to change the payout reward address with the new address you copied from the cold wallet
The following link will help you to accomplish this:
[Change Payout address in Space Pool](https://blog.pool.space/how-to-change-your-payout-address-in-space-pool-df7441f0bfdc)

## How to use your cold wallet

If in the future you want to send some of your xchs to a friend or an exchange, you will need to download the light wallet
from https://www.chia.net/download/ and install it in your computer (It should not be installed in the same computer you are farming chia).
You will need to import the 24 words in the lhe light wallet and you will need to connect the computer to internet.
It should sync pretty quick and once is done you can send your xchs and disconnect the computer from internet again and uninstall 
the light wallet if you will not be sending xchs in a regular basis.
