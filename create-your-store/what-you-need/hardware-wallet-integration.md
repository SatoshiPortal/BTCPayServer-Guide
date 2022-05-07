# Hardware Wallet Integration

1. [Download the BTCPay Vault app](https://github.com/btcpayserver/BTCPayServer.Vault/releases).
2. Install the Vault on your PC (Windows, MacOS or Linux).
3. Open the BTCPay Vault app.
4. Plug in the hardware wallet into your PC and make sure it’s in a wake up state.
5. Go to your BTCPay Server’s `Store > Settings > Wallet > Setup >`` `**`Import from a hardware wallet`.**
6. Grant the permission.
7. The public key will automatically be imported in the store and configured to an appropriate format.
8. Validate that the address shown on BTCPay is the same as the one on your device.
9. Click `Save`.

#### Spending funds <a href="#spending-funds" id="spending-funds"></a>

Once you’ve received funds to your wallet and you decide to spend them, you can sign the transaction with your hardware wallet, all inside BTCPay Server.

1. Open BTCPay Vault app on your PC.
2. Plug in the hardware wallet and make sure it’s in a wake up state.
3. In BTCPay Server, go to `Wallets > Manage > Send`.
4. Fill in the `Destination address` and the `Amount`.
5. Select `Sign with a hardware wallet`.
6. Verify the transaction on your hardware wallet and confirm it.
7. Broadcast the transaction.
