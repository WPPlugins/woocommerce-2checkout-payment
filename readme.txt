=== 2Checkout Payment Gateway for WooCommerce ===
Contributors: nmedia
Tags: payment gateway, 2co payment gateway, 2checkout woocommerce payment, woocommerce payment gateway
Donate link: http://www.najeebmedia.com/donate
Requires at least: 3.5
Tested up to: 4.7.4
Stable tag: 2.0
License: GPLv2
License URI: http://www.gnu.org/licenses/gpl-2.0.html

It's a WooCommerce extension allow clients make payment with 2Checkout.

== Description ==
2Checkout is best payment Gateway to accept payments online which allow your customers to make purchases in any of 8 payment methods, 15 languages, and 26 currencies. N-Media integrated 2Checkout Payment Gateway with WooCommerce. It is tightly integrated with WooCommerce Core API. When order is placed, user is navigated to 2CO awesome one page checkout page and All Billing & Shipping fields are also sent so customer will not type all Billing & Shipping information on 2CO. After payment the order is confirmed then user is sent back to the Thank You page.
= Features =
* Itemized Checkout - will display each item with SKU/ID
* Pass all billing and shipping data to 2CO purchase page
* Enable/Disable Test Mode

= Latest Releas now compatible with WooCommerce 3.0 =

= Signup with 2Checkout =
[Create 2Checkout Account](https://www.2checkout.com/referral?r=nmedia2co)

= Get PRO =
* Best support
* Inline Checkout Supported
* Customize Icon on Checkout Page
* Convert unsupported currencies to USD, pull live rates from Yahoo Converter
* [More detail About Pro Versoin](http://www.najeebmedia.com/2checkout-payment-gateway-for-woocommerce/ "Pro Feature")

== Installation ==
1. Upload plugin directory to the `/wp-content/plugins/` directory
2. Activate the plugin through the `Plugins` menu in WordPress
3. After activation, you can set options from `WooCommerce -> Settings -> Checkout` menu

== Frequently Asked Questions ==
= How to setup my 2Checkout Account? =
You must have a 2Checkout account for get your Account Number and set the return URL and notification URL. So go to 2Checkout and log in.

= How to found my Seller/Account Number? =
In 2Checkout Seller Area you will find your Account Number on the top right of the screen by clicking in the profile icon.

= How set page redirect =
Go into your **Account -> Site Management** and setup:

* Set the **Direct Return** as **Header Redirect (Your URL)**.
* Fill the Approved URL using a URL like:[http://yourdomain.com/?wc-api=wc_gateway_nm_twocheckout]
* Set your **Secret Word**
* Now you need to set **Notification URL** [See how](http://www.najeebmedia.com/best-payment-gateway-to-accept-payment-for-your-business "2Checkout Guide")
* Enable the **Order Created, Fraud Status Changed, Invoice Status Changed and Refund Issued** options and set the URLs like: [http://yourdomain.com/?wc-api=wc_gateway_nm_twocheckout]. [See how](http://www.najeebmedia.com/best-payment-gateway-to-accept-payment-for-your-business "2Checkout Guide")

= I am new to 2Checkout, can I have some quick overview? =
Yes, please visit this [Quick 2Checkout Guide](http://www.najeebmedia.com/best-payment-gateway-to-accept-payment-for-your-business "2Checkout Guide")


== Screenshots ==
1. 2Checkout options
2. WooCommerce Checkout page
3. Itemized checkout

== Changelog ==
= 2.0 =
* WooCommerce 3.0 Compatible
* Itemized Billing (Products, Tax, Shipping, Fees)
= 1.7 =
* Currency code passed to checkout
= 1.6 =
* BUG Fixed: Variable products prices were not correct, now it's fixed
* Set Product as Tangible or Intangible
* Sending Product ID to Cart Data
= 1.5 =
* fixed return url issue
= 1.4 =
* get_shipping() function is replaced with get_total_shipping
= 1.3 =
* Hash Mismatch issue fixed when client redirected to shop from 2checkout payment
= 1.2 =
* Now Secret word support added in plugin
* clear the cart once order is verified.
= 1.1 =
* fix callback url issue when payment is made.
* some labels are updated.
= 1.0 =
* It's first release











== Upgrade Notice ==
Nothing