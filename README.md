# Hempora Masternode Tutorial v1

# Step 1 - Generating Transaction and Getting Private Key
- Create a new address in your wallet
- Send !exactly! 100,000 HEMP to the address you created
- Go to the debug console via "Tools" and enter  ```masternode outputs```
- After your transaction has confirmed on the network, you will see your transaction output here
- Enter ```masternode genkey``` and save this, it is your private key for the next step
- Continue to the next step

# Step 2 - Setting up Linux Environment
- Launch a 64 bit, 16.04 Ubuntu VPS
- Enter:

```apt-get update -y && apt-get upgrade -y && wget https://raw.githubusercontent.com/Hempora/Hempora-node/master/hemp-mn.bash && bash hemp-mn.bash ```
- Enter "y" to the prompts that show and accept input 
- You will then need to enter your private key from the previous step
- When the installation is finished, you will see your node IP address and Private Key

# Step 3 - Configuring the Windows Configuration
- In your wallet, go to Tools -> "Open Masternode Configuration File"
- Follow the example in the configuration file
- The syntax is: Masternode_Name IP_ADDRESS:PORT PRIVATE_KEY TRANSACTION_NUMBER INDEX
- An example would like look this:

```mn1 127.0.0.1:28787 9fojh39ausdfoJAfdjf300qsdasd 7hnaks9dn23dqeiu24hr928hrt028ho284n3002nknadw21nkj2 1```

```name IP:PORT PRIVATE_KEY TX_ID TX_INDEX```

# Step 4 - Starting the Hempora Masternode
- Visit the transactions page in the wallet
- You can start your masternode after your transaction has been confirmed for at least 16 blocks
- Go to the Masternodes tab and click your masternode follow by Start-Alias!

# Thank you and please join our Discord or Telegram for support and more information.
