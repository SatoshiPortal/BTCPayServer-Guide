# Issuing Refunds



1. To refund an invoice, go in the `Invoices` page and click `Details` on the invoice.
2. Click `Issue a refund`
3. Select refund's payment method
4. Select the `amount` you want to refund
5. Share the link of this page with your customer

![](https://docs.btcpayserver.org/assets/img/claimingside.b4816192.jpg)

### Processing refund <a href="#processing-refund" id="processing-refund"></a>

Once a customer clicks on the link you've provided and adds their refund bitcoin address and claims the invoice, the next step is to process a refund.

1. Go to the `Payouts` tab in your sidebar.
2. Select the Payouts you want to process, go to actions and select `Approve and send`
3. Sign and broadcast the transactions.
4. The payout has now been signed and is in progress, awaiting confirmation on the blockchain. This is reflected to the claimant in their view.
5. After the transaction has been confirmed on the blockchain, the status of the payout will be `completed`.

![](https://docs.btcpayserver.org/assets/img/payouts-status5-completed1.24a1d84d.jpg)

![Customer's view after the refund has been successfully processed.](https://docs.btcpayserver.org/assets/img/claiment-completed1.4e877454.jpg)
