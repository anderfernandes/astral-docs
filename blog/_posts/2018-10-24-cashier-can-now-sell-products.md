---
layout: post
title:  Cashier can now sell products!
permalink: /:categories/:title
date:   2019-10-24 16:12:10 -0500
categories: alpha4
cover: /assets/images/Screenshot_20191024_160921.png
excerpt: Astral's Cashier interface can now sell products and provide a better user experience.
---

Hi everyone! I am here to talk about a feature that just got pushed to production. Cashier 
(Astral's point of sale interface) can now be used to sell products as well as tickets! This is
perfect if your science center has a gift shop, you can easily sell products, tickets or both to
your visitors. Let's get started!

<h4 class="ui header">1. Setup</h4>

The first thing you need to do is make sure you have categories for your products. In the screenshots
below I went to Admin => Settings => Products and created a new Product Type called "Gift Shop".

<img src="/assets/images/Screenshot_20191024_155930.png" class="ui fluid image" />

<h4 class="ui header">2. Adding products</h4>

Next, you should add products. Go to Admin => Products => Add Product and you should see something
like this:

<img src="/assets/images/Screenshot_20191024_160223.png" class="ui fluid image" />

Fill out this form with information on your product. Make sure if this is a product that you need
to keep track of, you track its inventory and put the how many you have on stock.

I went ahead and created two products and added two events since if we don't have events for the current
day or products to sell, Cashier won't show anything.

<img src="/assets/images/Screenshot_20191024_160729.png" class="ui fluid image" />

<img src="/assets/images/Screenshot_20191024_160653.png" class="ui fluid image" />

<h4 class="ui header">3. Selling products and tickets</h4>

All you have to do now is just tap/click the products/tickets you want to sell. They will be added
to a list of items to be checked out on the right as totals are calculated.

<img src="/assets/images/Screenshot_20191024_160753.png" class="ui fluid image" />

<img src="/assets/images/Screenshot_20191024_160812.png" class="ui fluid image" />

Note that the green "Charge" button will not allow you to charge a customer until:

- You have entered a tendered amount equal to or greater then the sale total
- Leave the "referece" field with less than two characters when payment is not made with cash
- The tendered amount is empty

The button will only be clickable if the information entered by the cashier is valid. Check everything
if you can't get it to become clickable.

Note how there are two tabs: one for tickets and one for products. Feel free to go back and forth
to add whatever your visitor wants to buy.

If the visitor wants to remove items from the sale, use the yellow and red buttons beside each
product/ticketsto do so. The yellow button removes one at a time and the red button removes all
of that particular item.

<img src="/assets/images/Screenshot_20191024_160921.png" class="ui fluid image" />

Once everything is good to go, the "Charge" button will be available. Click on it and the sale will
be completed.

<img src="/assets/images/Screenshot_20191024_160932.png" class="ui fluid image" />

<div class="ui divider"></div>

Today we are celebrating the second anniversary of Astral running in production! It has been a long
road and, although we are far from where we want to get, we are on the right path. For everyone who
believes in this project, thank you, from the bottom of my heart. Happy Halloween!!!