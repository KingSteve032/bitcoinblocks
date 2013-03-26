bitcoinblocks
=============
I made this Repo to backup my blocks file so I don't have to wait forever to download via P2P. I will be uploading a new update version of the file about every month if I can remember.

Installation Instructions
=========================
WARNING:
Only use these data files IF YOU HAVE AN EMPTY (or no) WALLET. While it "may" be fine to put these in with an existing wallet, and use the -rescan option, the target audience here is new bitcoin installs with an empty wallet.

Who needs this?
- Any first-time user of bitcoin, who wishes to avoid the lengthy block chain download through the p2p network.

Instructions:
- Download the block archive 
- blocks.zip (5.97 GB)
https://mega.co.nz/#!3EUFQKIC!WJrgUy4bLkev92nCuhu9_QBTme4ldyYhjZ2IlaKKL5A

last updated: 3/26/2013

- Unzip and copy blk*.dat files into your bitcoin data directory "C:\Users\*username*\Appdata\Roaming\bitcoin\blocks"
- Remove any database/log* files from your bitcoin data directory 
- Run bitcoin or bitcoind

What this does: 
- Resets the bitcoin block database and block database index to the state it was in at the time the snapshot was taken. 
- If you have a wallet with unprocessed transactions, the client may not recognize them. Thus, the above warning: Only use these data files IF YOU DO NOT ALREADY HAVE A WALLET.
