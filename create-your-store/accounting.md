# Accounting

BTCPay Server offers several tools that make **** bookkeeping easier.

### Invoice Export <a href="#invoice-export" id="invoice-export"></a>

![](https://docs.btcpayserver.org/assets/img/BTCPayInvoiceExport.16389f9c.png)

To export the **invoices:**

1. Go to Invoices;
2. Click on Export invoices
3. Select the export format (CSV/JSON) and download the file.&#x20;

{% hint style="info" %}
You can then customize the fields to fit your **business needs** and import the data into your **accounting software**, or create pivot tables from the exported data.
{% endhint %}

The fields are the following:

| Field name            | Description                                                                                                                                |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| ReceivedDate          | Date the payment has been received                                                                                                         |
| StoreId               | The store receiving the payment                                                                                                            |
| OrderId               | The order Id of the invoice                                                                                                                |
| InvoiceId             | The invoice ID                                                                                                                             |
| InvoiceCreatedDate    | Date of creation of the invoice                                                                                                            |
| InvoiceExpirationDate | Date of expiration of the invoice                                                                                                          |
| InvoiceMonitoringDate | Date your BTCPay Server ceases to monitor events of the invoice                                                                            |
| PaymentId             | Unique identifier of a payment                                                                                                             |
| Destination           | The destination address the customer paid to                                                                                               |
| PaymentType           | The type of payment (`OnChain`, `Offchain`)                                                                                                |
| CryptoCode            | Currency code of the method of payment (e.g. `BTC`)                                                                                        |
| Paid                  | Amount paid in the currency defined in CryptoCode                                                                                          |
| NetworkFee            | [Network fee](https://docs.btcpayserver.org/FAQ/Stores/#add-network-fee-to-invoice-vary-with-mining-fees) paid by the user in this payment |
| ConvertionRate        | The conversion rate at the time of invoice creation between `CryptoCode` and `InvoiceCurrency`                                             |
| InvoiceCurrency       | The currency code of the invoice (e.g. `USD`)                                                                                              |
| InvoiceDue            | The amount still due to fully pay the invoice after this payment (minus `NetworkFee`, denominated in `InvoiceCurrency`)                    |
| InvoicePrice          | The total price of the invoice (minus Network Fee, denominated in `InvoiceCurrency`)                                                       |
| InvoiceItemCode       | The item code afferent to the products/services billed by the invoice                                                                      |
| InvoiceItemDesc       | The item description afferent to the products/services billed by the invoice                                                               |
| InvoiceFullStatus     | The full status of the invoice (e.g. `expired (paidPartial)`)                                                                              |
| InvoiceStatus         | The simplified status of the invoice (e.g. `expired`)                                                                                      |
| InvoiceException      | The status of the invoice (e.g. `paidPartial`)                                                                                             |

### QuickBooks Online Connector for BTCPay Server <a href="#quickbooks-online-connector-for-btcpay-server" id="quickbooks-online-connector-for-btcpay-server"></a>

**BTCQBO** is a third-party plugin that **enables QuickBooks Online users to connect their BTCPay server** easily. Besides **bookkeeping**, users can quickly **generate invoices from their QuickBooks**. For more information about the BTCQBO and all the features it offers, [check the plugin repository](https://github.com/JeffVandrewJr/btcqbo).
