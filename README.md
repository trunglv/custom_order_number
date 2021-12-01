# Betagento
## Custom Order Number 

### Overview:
This extension is implemented to help you manage an order number more flexible. Default order number functionality of Magento just a simple one, just manages increment numnber. You can do more with my extension.

Example, you want to make an order number like this : `DE-B2B-04-00023`. DE is country code, B2B is a customer group and 04 is a month when an order is created. So please read more detail how to do it with my extension.

### Key features:
- use institute expression to define a order number, example:  `{country_code}-{customer.customer_group}-{month}-{counter}`
- Work for Orders, Invoices and Shipments as well

### How to use it:
#### Configuration
Go to Configuration >> Betagento >> Order Number
--- Image ---
##### Expression:
Variables already supported:
```
{count} : Count
{date} : Date number 
{month} : Month number 
{year} : Year number
{website_code} : Website code
{customer_group} : Customer Group
```
Shipping Address attributes 

```
billing_address.company : Company
```
Shipping Address attributes 

```
{shipping_address.country_id} : Country 
{shipping_address.postcode} : Post code
```

If you want more, pls contact me (Trung) ["luuvantrung@gmail.com"]

##### Zero Padding : 
Number zero is padded before a counter, default is 9

#### Support
Adustment or to add more features is possible -- so if you are interested, pls contact me. Again via (Trung) ["luuvantrung@gmail.com"]

Issues : You can post an issues here.

Free to fix any bugs/issues of all verions of the extension (For all of a functionality term, a coding standard term, security term). Regardless, you need to pay me a coffee. 


## About Betagento: 
My name is Luu Van Trung. Betagento is my personal bussiness to provide Magento extensions and services. 








