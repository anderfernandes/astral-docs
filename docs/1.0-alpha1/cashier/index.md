---
layout: page
title: Docs | 1.0-alpha1 | Cashier
permalink: /docs/1.0-alpha1/cashier/
---

<h1 class="ui dividing header">
  <i class="inbox icon"></i>
  <div class="content">
    Cashier
    <div class="sub header">
      Sales, tickets, reports, query sale data
    </div>
  </div>

</h1>

<div class="ui icon message">
  <i class="info circle icon"></i>
  <div class="content">
    <div class="header">Use modern browsers</div>
    We recommend using modern browsers such as the latest versions of Chrome, Firefox, Safari or Edge. Internet Explorer is not guaranteed to work.
  </div>
</div>

<div class="ui icon message">
  <i class="info circle icon"></i>
  <div class="content">
    <div class="header">JavaScript should be enabled</div>
    Make sure you have JavaScript enabled in your browser or some features of Astral may not work properly.
  </div>
</div>

##  <i class="hashtag icon"></i> Accessing Cashier

After Astral has been setup in your organization, you may login using the URL provided to you by the person who set it up. As soon as you access the URL in your browser, you will see the login screen. After you enter your credendials, you will be taken to the Admin dashboard, regardless of your account type.

<img src="/assets/images/login.png" class="ui image" />

If you don't have an account, you should create one by clicking in Register. Fill out and submit the form and you should be good to go.

<img src="/assets/images/register.png" class="ui image" />

After you create and account, use your credentials to log in.

Upon login, you will be taken to Admin Dashboard. From there, in order to access Cashier, you have two options:

1. Click on the Cashier button on the top right corner of the screen. The button is located right by where your name is located.
2. Clicking in the <i class="sidebar icon"></i> button to access the Sidebar Menu. The last option is Cashier. Click on it.

Cashier will always be open on a new tab.

## <i class="hashtag icon"></i> Cashier

Cashier is the main screen in Cashier. What you will see there depends on wether nor not you have events set up for today. If your account allows, you need to add events. Otherwise, contact a supervisor or someone with Admin access and tell them to add the Event(s) in Admin.

Events will be ordered according to their start time. Events starting in the morning will be shown before events starting in the afternoon or evening.

Each Show cover and data close to it represent data for that event.

<div class="ui icon message">
  <i class="info circle icon"></i>
  <div class="content">
    <div class="header">Cashier only shows today's events</div>
    Cashier will only show events that are happening today. If you come for a shift and you see the message "No shows!", it means that your supervisor or someone with Admin access should add them in Admin.
  </div>
</div>

<div class="ui icon message">
  <i class="info circle icon"></i>
  <div class="content">
    <div class="header">About Event data updates</div>
    Event data only refreshes upon page refresh.
  </div>
</div>

### Selling Tickets

Only the appropriate tickets will be available for sale in a particular Event. You should not see, for example, a Special Event ticket available in a Matinee.

In order to sell, for example, two matinee tickets for an Event happening at a particular time, click (or tap if you are in a touchscreen) on the green button that has the ticket type twice. Each click/tap adds one ticket to the sale. To remove tickets, click/tap the red minus button corresponding to a particular ticket. Select the Customer you are selling to, the tendered amount in the Tendered field, select the payment method in the Payment Method dropdown, enter a Reference for the payment in the Reference field if necessary and click/tap the green Charge button.

Cashier will grey out the Tendered field and the Charge button if you have no tickets to sell.

<div class="ui icon message">
  <i class="info circle icon"></i>
  <div class="content">
    <div class="header">About the Customer field</div>
    You can click on it once and type the customer's name to find him/her. If this customer is in the database, his name will pop up. Otherwise, the customer will have to be added, a task that can be done only by a user with access to Admin.
  </div>
</div>

<div class="ui icon message">
  <i class="info circle icon"></i>
  <div class="content">
    <div class="header">About the Tendered field</div>
    Make sure you enter the correct information in the Tendered field. If the sale is for $ 20, you may enter 20, 20.0 or 20.00.
  </div>
</div>

<div class="ui icon message">
  <i class="info circle icon"></i>
  <div class="content">
    <div class="header">About the Payment Method field</div>
    Do not forget to select the correct Payment Method for a sale. Non cash payment methods require a reference always.
  </div>
</div>

<div class="ui icon message">
  <i class="info circle icon"></i>
  <div class="content">
    <div class="header">About the Reference field</div>
    If your sale is not cash, Astral will not let you finish the sale if you don't enter a reference. This is usually the last 4 digits of the customer's card or the check/money order number.
  </div>
</div>

If you did everything correctly, you will see a message of success for the sale. Otherwise, you may have to start over.

## <i class="hashtag icon"></i> Finding a Sale

You can query a search by entering at least one piece of information about it. Sending a blank form will not display any results. Find Sale is located in the Sidebar Menu.

Enter whatever you know about the sale and click the green Find Sale button. If you don't know much about the sale you are looking for, start by entering a Sale Total that you can obtain from your credit card machine report or by trying to guess the Sale Payment Method.

## <i class="hashtag icon"></i> Refunds

A Refund does not delete or cancel a sale. It actually marks it as a refund.

In order to do a Refund, you need to find the sale using the Sidebar Menu item **Find Sale**. Read **Finding a Sale** for more information.

After you find the sale you want to refund in the **Find Sale** results, click on it and you will be taken to the Sale information page. At the top right corner of that screen, there will be a red Refund button. Enter the sale information to confirm that you know what you are doing and not doing it by accident and click Refund.

If you did everything correctly, the Sale will be marked as refunded and the Sale information page will have red letters.

## <i class="hashtag icon"></i> Reports

Cashier has basic payment reporting functions to help in your conciliation process. As of release 1.0-alpha1, there are two reports: **Closeout Report** and **Transaction Detail Report**.

<div class="ui icon message">
  <i class="info circle icon"></i>
  <div class="content">
    <div class="header">About Report data</div>
    Both reports only show data that you entered onto the system. Also, the data range is between the beginning of the day and the moment you request the report.
  </div>
</div>

### Closeout Report

This reports breaks down payments made in cash, card and check. The payments displayed in this report are only the ones taken by the cashier logged in cashier asking for it.

### Transaction Detail Report

This reports shows a table in which every line is a payment. The payments displayed in this report are only the ones taken by the cashier logged in cashier asking for it.

<div class="ui icon message">
  <i class="info circle icon"></i>
  <div class="content">
    <div class="header">Printing a Report</div>
    You may print a report using the File<i class="right chevron icon"></i>Print menu in your browser or using Ctrl+P.
  </div>
</div>

<div class="ui icon message">
  <i class="info circle icon"></i>
  <div class="content">
    <div class="header">About Refunds in Transaction Detail Reports</div>
    Refunds will be shown as a negative sign and red table row in Transaction Detail Reports. Right above it, the payment that refers to it will be shown as well.
  </div>
</div>

## <i class="hashtag icon"></i> Logging Out

Click in the Sidebar button at the top left of the screen and click in the Logout button.

##  <i class="hashtag icon"></i> My Account

This is where you go to change your account information if you don't type anything in the password fields, your password won't change. Click save if changes have been made or click back to return to Dashboard.

<div class="ui icon message">
  <i class="info circle icon"></i>
  <div class="content">
    <div class="header">Protect your credentials</div>
    Do not share your account information with anyone. Your account is like and ID card and everything you do in Astral is recorded under the logged user credentials. If you are going to be away from the screen, let's say, to go to the restroom, we recommend you logging out. Make sure you save any new data you are entering into the system.
  </div>
</div>

##  <i class="hashtag icon"></i> Members

The **Members** area of Cashier will assist you in adding your non-profit's members to the system so you can track and offer the benefits of a Membership.

Before using this feature, make sure you organization has all membership levels set up with their respective benefits and duration.

### Adding a Member

Click in the Menu icon and click in Members. Click on the Add Member icon and fill in all their information. Select the membership package and take their payment.

<div class="ui icon message">
  <i class="info circle icon"></i>
  <div class="content">
    <div class="header">Adding a new member also creates a Sale!</div>
    Completing a membership creates a Sale for the person you are selling the membership for.
  </div>
</div>
