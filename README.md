# Betagento
## Magento2 - Custom Order Number 

### Overview:
I implement this extension to help you manage an order number more flexibly. The default order number functionality of Magento is just a simple one; it just manages increment numbers by store scope, and you can do more with my extension.

For example, you would like to make an order number like this: DE-B2B-04-00023. Which: DE is country code, B2B is a customer group, and 04 is a month when a customer is placing an order. So please read more detail on how to do it with my extension.


### Key features:
- use easy-to-use expression to define an order number, example:  `{website_code}-{customer.customer_group}-{month}-{SEQUENCE_NUMBER}`
- Work for Orders, Invoices, and Shipments as well

### How to use it:
#### Configuration
Go to Store >> Configuration >> Betagento >> Custom Order Number

![image](https://user-images.githubusercontent.com/820411/144455147-dbf0ef01-4250-4887-b414-1ef13ac89bb5.png)

![image](https://user-images.githubusercontent.com/820411/144455202-8f7098b4-cf97-41a1-8b00-69f503c7c7b2.png)

![image](https://user-images.githubusercontent.com/820411/144455233-98211803-f867-4c1e-be92-1654725b844d.png)



#### 1. Pattern/Expression : Where to define a format of a order numebr 
Variables already supported:

```
{SEQUENCE_NUMBER} : Sequence Number (0000xxx)
{date} : Date number 
{month} : Month number 
{year} : Year number
{website_code} : Website code
{customer_group} : Customer Group
```
Shipping Address attributes 

```
billing_company : Company
billing_country_id : Country ID (DE,DK)
billing_postcode : Country ID (DE,DK)
```
Shipping Address attributes 

```
{shipping_country_id} : Country 
{shipping_postcode} : Post code
```

If you want more, pls contact me (Trung) ["luuvantrung@gmail.com"]

#### 2. Zero Padding : 
Number zero is padded before a counter, default is 9

#### 3. Use Sequence Per Wesbite Scope : 
Sequence number will calculate by website scope not store scope.

### Support
You want to adjust it or to add more features is possible -- so if you are interested, pls contact me. Again via (Trung) ["luuvantrung@gmail.com"]

Issues : You can post an issues on a given private repository if you are allowed.

Free to fix any bugs/issues of all verions of the extension (For all of a functionality term, a coding standard term, security term). Regardless, you need to pay me a coffee. 


## About Betagento: 
My name is Luu Van Trung. Betagento is my personal bussiness to provide Magento extensions and services. 

## Purchase process:

- Send me money via a Paypal link below - or send email (luuvantrung@gmail.com), skype: beta.trunglv to request a purchase or demo:

- I will send you a access into private repository with opensource code and installation guide.

<p>
<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=6DNEKNWFVXKKA" 
target="_blank">
<img src="https://www.paypalobjects.com/en_US/GB/i/btn/btn_buynowCC_LG.gif" alt="PayPal this" 
title="PayPal – The safer, easier way to pay online!" border="0" />
</a>
</p>

<div id="smart-button-container">
      <div style="text-align: center;">
        <div id="paypal-button-container"></div>
      </div>
    </div>
  <script src="https://www.paypal.com/sdk/js?client-id=AT7GE-inDnrag6My-dYCd6_QIWOEAJadIH1C6Js02WGcctKVUWtwCOY4KEaxmifTRUf1xrbLHjMn9znv&enable-funding=venmo&currency=USD" data-sdk-integration-source="button-factory"></script>
  <script>
    function initPayPalButton() {
      paypal.Buttons({
        style: {
          shape: 'rect',
          color: 'gold',
          layout: 'vertical',
          label: 'buynow',
          
        },

        createOrder: function(data, actions) {
          return actions.order.create({
            purchase_units: [{"description":"Magento2 - Custom Order Number Extension","amount":{"currency_code":"USD","value":49}}]
          });
        },

        onApprove: function(data, actions) {
          return actions.order.capture().then(function(orderData) {
            
            // Full available details
            console.log('Capture result', orderData, JSON.stringify(orderData, null, 2));

            // Show a success message within this page, e.g.
            const element = document.getElementById('paypal-button-container');
            element.innerHTML = '';
            element.innerHTML = '<h3>Thank you for your payment!</h3>';

            // Or go to another URL:  actions.redirect('thank_you.html');
            
          });
        },

        onError: function(err) {
          console.log(err);
        }
      }).render('#paypal-button-container');
    }
    initPayPalButton();
  </script>

- Don't worry -- drop messages to me and video call is welcome!

