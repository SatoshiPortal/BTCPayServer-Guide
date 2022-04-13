# Payment Requests

Payment Requests are a feature which allows BTCPay store owners to create long-lived invoices. Funds paid to a payment request use the exchange rate at the time of payment. This allows users to make payments at their convenience without having to negotiate or verify exchange rates with the store owner at the time of payment.

Users can pay requests in partial payments. The payment request will remain valid until it is paid in full or if the store owner requires an expiration time. Addresses are never reused.&#x20;

{% hint style="success" %}
A new address is generated each time the user clicks pay to create an invoice for the payment request.
{% endhint %}

Store owners can also print payment requests (or export invoice data) for record keeping and accounting. BTCPay automatically labels invoices as Payment Requests in your store's invoice list.

### Create a Payment Request <a href="#create-a-payment-request" id="create-a-payment-request"></a>

Click Payment Requests > Create new payment request

![](https://docs.btcpayserver.org/assets/img/CreatePaymentRequest.197d6a11.png)

Provide the Request Name, Amount, Display Denomination, Associated Store, Expiration Time & Description (Optional)

Select the option _Allow payee to create invoices in their own denomination_ if you want to allow partial payments to be made.

{% hint style="danger" %}
Payment requests are store-dependent, which means that each payment request is associated with a store during creation. Be sure to have a wallet connected to your store which the payment request belongs to.
{% endhint %}

Click Save & View to review your payment request.

![](https://docs.btcpayserver.org/assets/img/NewPaymentRequest.92a9c243.png)

{% hint style="success" %}
BTCPay creates a URL for the payment request. Share this URL to view your payment request.
{% endhint %}

{% hint style="info" %}
The status will appear as **Settled** if payment has been received in full. If only partial payment was made, the Amount Due will show the balance due.
{% endhint %}

### Customize Your Payment Requests <a href="#customize-your-payment-requests" id="customize-your-payment-requests"></a>

* **Invoice Amount** - Set Requested Payment Amount
* **Denomination** - Show Requested Amount in Fiat or Cryptocurrency
* **Payment Quantity** - Allow only single payments or partial payments
* **Expiration Time** - Allow payments until a date or without expiry
* **Description** - Text Editor, Data Tables, Embed Photos & Videos
* **Appearance** - Color and Style with CSS Themes
