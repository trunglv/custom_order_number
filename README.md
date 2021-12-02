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
Go to Store >> Configuration >> Betagento >> Custom Order Number

![image](https://user-images.githubusercontent.com/820411/144455147-dbf0ef01-4250-4887-b414-1ef13ac89bb5.png)

![image](https://user-images.githubusercontent.com/820411/144455202-8f7098b4-cf97-41a1-8b00-69f503c7c7b2.png)

![image](https://user-images.githubusercontent.com/820411/144455233-98211803-f867-4c1e-be92-1654725b844d.png)



##### 1. Pattern/Expression : Where to define a format of a order numebr 
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

##### 2. Zero Padding : 
Number zero is padded before a counter, default is 9

##### 3. Use Sequence Per Wesbite Scope : 
Sequence number will calculate by website scope not store scope.

#### Support
Adustment or to add more features is possible -- so if you are interested, pls contact me. Again via (Trung) ["luuvantrung@gmail.com"]

Issues : You can post an issues here.

Free to fix any bugs/issues of all verions of the extension (For all of a functionality term, a coding standard term, security term). Regardless, you need to pay me a coffee. 


## About Betagento: 
My name is Luu Van Trung. Betagento is my personal bussiness to provide Magento extensions and services. 

Purchase process:

- Send me money via
<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=6DNEKNWFVXKKA" 
target="_blank">
<img src="https://www.paypalobjects.com/en_US/GB/i/btn/btn_buynowCC_LG.gif" alt="PayPal this" 
title="PayPal – The safer, easier way to pay online!" border="0" />
</a>
- I will send you a access into private repository with opensource code and installation guide.


