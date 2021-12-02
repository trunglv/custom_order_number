# Betagento
## Custom Order Number 

### Overview:
I implement this extension to help you manage an order number more flexibly. The default order number functionality of Magento is just a simple one; it just manages increment numbers by store scope, and you can do more with my extension.

For example, you would like to make an order number like this: DE-B2B-04-00023. Which: DE is country code, B2B is a customer group, and 04 is a month when a customer is placing an order. So please read more detail on how to do it with my extension.


### Key features:
- use easy-to-use expression to define an order number, example:  `{country_code}-{customer.customer_group}-{month}-{SEQUENCE_NUMBER}`
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

Issues : You can post an issues here.

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

- Don't worry -- drop messages to me and video call is welcome!

