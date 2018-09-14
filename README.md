# bitcoin-node-info-python
Uses python to grab bitcoin node information and write html file, use cron job to automatically update



The node example is my node, this is the script that I'm using.

Download this script

Put it anywhere on your server and change the RPCUSER/PASS, NODEADDR and BITCOINADDR.

Run the script to update every time. You can also use it to create a chron job.

To run the script, after editing the values above, put it anywhere and type: python btc-update.py

If it just returns, that means it works :)

Note: If you get an error, you’ll need to install BitcoinRPC for the script to work. Go here: https://github.com/jgarzik/python-bitcoinrpc Follow Jeffs simple instructions. Once BitcoinRPC is installed, run the node script again and it will update!

Good luck!
