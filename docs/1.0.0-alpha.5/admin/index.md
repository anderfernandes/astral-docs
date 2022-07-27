---
layout: page
title: Docs | 1.0.0-alpha4 | Admin
permalink: /docs/1.0.0-alpha.5/admin
---

<h1 class="ui dividing header">
  <i class="sun outline icon"></i>
  <div class="content">
    Admin
    <div class="sub header">
      Manage all aspects of your non profit
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

<div class="ui dividing header" id="accessing-admin"><i class="hashtag icon"></i>Accessing Admin</div>

After Astral has been setup in your organization, you may login using the URL provided to you by the person who set it up. As soon as you access the URL in your browser, you will see the login screen. After you enter your credendials, you will be taken to the Admin dashboard, regardless of your account type.

<img src="/assets/screenshots/1.0.0-alpha2/Screenshot_20180319_195508.png" class="ui image" />

If you don't have an account, you should create one by clicking in Register. Fill out and submit the form and you should be good to go.

<img src="/assets/screenshots/1.0.0-alpha2/Screenshot_20180319_201753.png" class="ui image" />

After you create and account, use your credentials to log in.

<div class="ui icon message">
  <i class="info circle icon"></i>
  <div class="content">
    <div class="header">Access Control</div>
    By default users who register themselves will not see much. Make sure you change their role if they are going to be working with Admin.
  </div>
</div>

<div class="ui dividing header" id="dashboard"><i class="hashtag icon"></i>Dashboard</div>

The Dashboard is were you will have an overview of your organization. There is plenty of information there and it should be pretty self explanatory.

<img src="/assets/screenshots/1.0.0-alpha2/Screenshot_20180319_195840.png" class="ui image" />

### Overall Earnings

This graph shows the amount of money collected in the last seven days, broken down by each day. The data only comes from Sales marked as "completed".

### Calendar

This is where you'll see what groups will come to visit your non-profit and what events will happen today. You can switch between Reservatons and Events just like you can do in Calendar. You can also use the arrows to go back or forward one or more days. Click in the calendar icon between the arrows to go back to today in the calendar.

### Bulletin

This is where you're going to see bulletin posts from the last seven days. You can see the post's author, category, importance, date created and number of replies.

### Attendance

These graphs break down the amount of people who came to visit your non-profit by tickets sold and by demographics (ticket type) in the last seven days.

### Database Overview

Under the Attendance box you can see the amount of shows, users, organizations and members in your Astral database.

### Feed

In the Feed box you can see data on the latest seven sales. Click on the links to see information on the sale, cashier or show.

<div class="ui dividing header" id="top-menu"><i class="hashtag icon"></i>Top Menu</div>

The Top Menu is a global menu at the top of every screen in Admin. Use it to see where you are, as the menu shows the portion of Admin you are currently in. It also has a button to access [Cashier](../cashier) at any moment, which will open it in a new browser tab.

If you click in your name, you will be given access to a screen that will allow you to change your account information such as name and password.

<div class="ui dividing header" id="my-account"><i class="hashtag icon"></i>My Account</div>

This is where you go to change your account information. _If you don't type anything in the password fields, your password won't change_. Click save if changes have been made or click back to return.

<img src="/assets/images/my-account.png" class="ui image" />

<div class="ui icon message">
  <i class="info circle icon"></i>
  <div class="content">
    <div class="header">Protect your credentials</div>
    Do not share your account information with anyone. Your account is like and ID card and everything you do in Astral is recorded under the logged user credentials. If you are going to be away from the screen, let's say, to go to the restroom, we recommend you logging out. Make sure you save any new data you are entering into the system.
  </div>
</div>

<div class="ui dividing header" id="sidebar"><i class="hashtag icon"></i>Sidebar</div>

Clicking in the <i class="sidebar icon"></i> button to access the Sidebar. This button will be called the Sidebar Button from now on and the menu that comes when you click on it will be called the Sidebar.

Some sidebar items have subitems that allow faster access to their sub options.

Each sidebar option is explained below.

<div class="ui dividing header" id="shows"><i class="hashtag icon"></i>Shows</div>

Manage all shows in your non-profit. If you are running, for example, a Planetarium, you have a few shows/movies/documentaries in your catalog and here is where you would add them.

<img src="/assets/screenshots/1.0.0-alpha2/Screenshot_20180319_195956.png" class="ui image" />

The shows are displayed in groups of 10, in the order in which they were added, descending. That means, shows recently added come first.

You may click in a show at any time to see details on it. Clicking on the three dots by each of the shows will show you a menu where you can click on View or Edit.

You may also filter shows by name, duration and type.

### Adding a Show

At the top of the screen, right below the Menu, you will see the Add Show button. That's where you go to add a new show.

<img src="/assets/screenshots/1.0.0-alpha2/Screenshot_20180319_200028.png" class="ui image" />

In order to add a show, ou will need the following data:

- Show Name (required)
- Show Type (required)
- Duration (in minutes, required)
- Cover (URL)
- Description (required)

Show Name is a required field. Enter the show name. Most specials characters are allowed.

Show Type is a required field. Shows can have different types. For example, it may be a full dome Planetarium show, or a Laser Light show. Those are custom types that can be added in Settings <i class="right chevron icon"></i> Show Types. Read **Adding Show Types** for more information.

Duration is a required field. Put the show duration in minutes. If the show is more than an hour long, put the minutes anyways. We recommend rounding show durations up to the nearest integer.

Cover is not a required field and it takes a URL, which means, _a link to an image file somewhere on the web or your intranet. The link must end with *png* or *jpg*_. If no cover is entered, a placeholder image will be the cover until you set one.

Description is a required field. Use this field to describe the show. Astral allows you to format your description using **HTML** and **Markdown** markup languages. You can have, for example, bold text, paragraphs, bulleted lists, ordered lists, etc.

<div class="ui dividing header"><i class="hashtag icon"></i>Calendar</div>

Displays all your **sales** (reservations) and **events** (and sales only) in a calendar format. You can switch between reservations view and events view by clicking on the button on the top right corner of the screen.

<img src="/assets/screenshots/1.0.0-alpha2/Screenshot_20180319_200127.png" class="ui image" />

Calendar automatically fetches new sales and updates, which means that if somebody else adds a sale elsewhere, this sale will be automatically updated on other people's calendar if they have it open.

At the top of Calendar you will have buttons that will assist you in creating a new sale and/or event. Depending on what you have on the database, you may be able to just create and event and then create a sale and you will have a new item on Calendar.

If there are multiple shows under one timeslot, the events are going to be split. You may click in one event to access its data and edit it from there if you need to. For more information on how to Edit Events, please access the Events portion of Admin's docs.

You may also change Calendar's view using the second line of buttons (the grey ones). As of release 1.0-alpha2, the views available are Single Day View, Week View (the default view) and Month View.

You may use Single Day View to see all the Sales for a particular day.

Week View displays all the events in a particular week.

Month View displays all the events in a particular month.

You may click on Today to see what events you have today.

You can check different timeframes by clicking in the arrows right below the Create Event button, at the top left corner.

### Creating an Event

You can create new events by clicking the "New Event" button.

Before you create an Event, make sure you have added the show for that event beforehand. Please read **Adding a Show** for more information.

<img src="/assets/screenshots/1.0.0-alpha2/Screenshot_20180319_200155.png" class="ui image" />

Also, you need to have Event Types. Please read **Adding Event Types** for more information.

The Seats field read automatically from Settings, but the value you set here overrides it.

The default start and end date and times for events by default will be one hour apart when you set and event's start time. You may have a shorter or longer end date and time. The length of your event has nothing to do with your show event's length.

In Memo, put important notes about the Event. As of release 1.0-alpha1, memos are on a per Event basis rather than by User basis, which means that you can only add only one Memo per Event. You may put your name and/or initials and date after each line people know who and when they were written.

### Viewing an Event

In Calendar, when you have Events view selected, you may view information on an event by clicking on it (as of 1.0.0-alpha2, events are seen as blue colored boxes in Calendar and Sales/Reservations are grey).

Clicking in any Event in the calendar will take you to that Event's information page. In that page, you can see a lot of information on events, such as who created them and when, what show is the event having, the last time the event was updated and Memo.

<img src="/assets/screenshots/1.0.0-alpha2/Screenshot_20180319_200053.png" class="ui image" />

As of 1.0.0-alpha2, you can also see what sales are attached to that event.

Right above that information there are a couple of buttons with actions.

The Back button takes you back to Calendar.

The Edit This Event button takes you to a page very similar to **Create an Event**, except that this time it will have all the data you entered when you created the Event. Please read **Editing an Event** for more information.

The _Create Another Event_ button takes you to **Create an Event**.

Depending on your access control rules, you may see the Delete Event button. Make sure this isn't a past Event as we do not recommend Delete Events that have sales attached to them.

<div class="ui icon message">
  <i class="info circle icon"></i>
  <div class="content">
    <div class="header">About deleting events</div>
    Make sure there are no events attach to a sale before you delete them.
  </div>
</div>

### Editing an Event

The Edit Event page allows you to change anything on a particular Event. Make sure that you really want to do this, as there may be sales attached to this Event.

As far as the information available, it is very similar to the one in **Create an Event**. Please read it if you need to know more.

<div class="ui dividing header" id="sales"><i class="hashtag icon"></i>Sales</div>

This is most likely the screen your organization will be using the most. This is where you will manage Sales.

<img src="/assets/screenshots/1.0.0-alpha2/Screenshot_20180319_215918.png" class="ui image" />

### Creating a Sale

To create a new Sale, click in the New Sale button, select what kind of event you are creating the sale for (remember to have event types set up in settings), and fill out the form. You may add a payment if one is being made at the moment the sale is being created, or you can add payments later. Astral does support multiple payments in this screen, which means that your are able to take a partial payment such as a deposit or a down payment. Don't forget to mark the Sale as completed if a payment has been made in full.

<img src="/assets/screenshots/1.0.0-alpha2/Screenshot_20180321_093914.png" class="ui image" />

Alternatively, you may create a new sale in calendar. The link there will take you to the "New Sale" screen.

<div class="ui icon message">
  <i class="info circle icon"></i>
  <div class="content">
    <div class="header">Don't forget to mark a Sale as "completed" if it has been paid in full</div>
    Very important, don't forget!
  </div>
</div>

### Adding Payments to a Sale

Find the Sale that is going to be paid for, click the Edit button that corresponds to it. _Note that there are two tabs in the middle of the screen: Sale Information and Payment Information._ Click in the Payment Information tab and fill out the Payment part of the form. Astral does support deposits, down payments and multiple payments. Enter the amount, the method and a reference.

<img src="/assets/screenshots/1.0.0-alpha2/Screenshot_20180321_094537.png" class="ui image" />

<div class="ui icon message">
  <i class="info circle icon"></i>
  <div class="content">
    <div class="header">Payment Reference</div>
    This field should receive information such as the last 4 of a Credit Card, Check Number or Money Order number. This field is not required for Cash sales, although you may use it.
  </div>
</div>

### Editing a Sale

To edit a Sale, click in the Edit button that corresponds to the Sale you want to make changes to. Once you are on the Edit screen, you can change anything, except payments that have been made.

The Edit Sale screen is very similar to the Create Sale one.

<div class="ui icon message">
  <i class="info circle icon"></i>
  <div class="content">
    <div class="header">Memos</div>
    Sales that are being edited require a memo. In the memo field, write why you are making changes. You can't save and edited sale if you don't leave a memo.
  </div>
</div>

### Viewing a Sale

In Sales, when you click in the blue "eye" icon, you will be taken to View Sale. You can also get there by clicking in one of the available Sales inside a View Event.

<img src="/assets/screenshots/1.0.0-alpha2/Screenshot_20180321_094429.png" class="ui image" />

This screen is very important. All the information on that sale will be available here. You can see who and when it was created/last modified, customer information (an individual, a member, an organization or both) as well as event information (when and how many tickets), price, payments and memos. Note that individuals, organizations and shows have a text of blue color. These are links so you can quickly access their information.

<div class="ui dividing header" id="reports"><i class="hashtag icon"></i>Reports</div>

As of version 1.0.0-alpha2, admin users can view/print the following reports:

<img src="/assets/screenshots/1.0.0-alpha2/Screenshot_20180319_200339.png" class="ui image" />

### Cashier Reports

The first Cashier report you will encounter is the Closeout Report. This report lists payment totals split by payment method (cash, card, check) for the selected payment user and the selected date range.

The second Cashier report is the Transaction Detail Report. This report lists information on every single payment taken by a payment user.

### Royalties Reports

The Royalty Report shows a wide range of data on the selected show, including how much money that show made before and after tax, attendance and number of showings, with graphs. This is perfect to show to any company your non-profit has to pay royalties to.

### Membership Reports

The New Members Report shows a list of data on members who signed up for a membership in the selected date and time range.

<div class="ui dividing header" id="members"><i class="hashtag icon"></i>Members</div>

Your organization needs to define the available membership packages. Prices, duration and maximum number of seondaries must be defined before your organization starts selling memberships.

<img src="/assets/images/membership.png" class="ui image" />

The **Members** area of Admin will assist you in adding your non-profit's members to the system so you can track and offer the benefits of a Membership.

Before using this feature, head to Settings and go to the Membership tab. Make sure you have all membership levels set up with their respective benefits and duration.

<div class="ui icon message">
  <i class="info circle icon"></i>
  <div class="content">
    <div class="header">Transfering members from an old system</div>
    If you have members in a different ticketing system and want to transfer them to Astral, we suggest you to create a new membership level that costs $ 0 and then add them following the steps below, not forgetting to set when their membership started.
  </div>
</div>

<div class="ui icon message">
  <i class="info circle icon"></i>
  <div class="content">
    <div class="header">Make sure the member has a user account</div>
    Before adding a member, make sure the new member has a user account. If the person doesn't, you may create one then go back to Admin's Member or create it in Cashier.
  </div>
</div>

### Adding a Member

Click in the Menu icon and click in Members. Click on the Add Member icon and fill in all their information. Select the membership package and take their payment.

<img src="/assets/images/add-member.png" class="ui image" />

<div class="ui icon message">
  <i class="info circle icon"></i>
  <div class="content">
    <div class="header">Membership elegibility</div>
    The dropdown on the screen shown in the screenshot above will only have users eligible for a membership. First of all, they must be added in the database through the [Users](#users) menu. If they already are in the database, all you have to do is make a person a member by selecting their name from the dropdown. Current user will not be shown in this dropdown, event if their membership have expired.
  </div>
</div>

<div class="ui icon message">
  <i class="info circle icon"></i>
  <div class="content">
    <div class="header">Adding a new member also creates a Sale!</div>
    Completing a membership creates a Sale for the person you are selling the membership for.
  </div>
</div>

### Viewing a Member's Information

To see details on a particular member, click on the blue view button.

<img src="/assets/images/member-details.png" class="ui image" />

### Adding a Secondary

To add a secondary, click on the Add a Secondary button. This will only be clickable if theere are secondaries spots available for that particular membership type.

<div class="ui icon message">
  <i class="info circle icon"></i>
  <div class="content">
    <div class="header">A secondary must be added as a user first!</div>
    The name options under secondary don't come from outer space. They must be added as a user first if they haven't already.
  </div>
</div>

### Viewing/Priting Membership Receipt

After adding someone as a member, you can view and print the membership receipt by clicking in the View Membership Receipt button. The receipt will be open in a new tab. The receipt will show all information relative to the membership such as cost, expiration date, etc. You can click in the blue button with a printer icon to print it or you can close return by clicking in the button with an "X" or closing the tab.

### Viewing/Printing Membership Card

In the Member Information screen you can click in the yellow "View Card" button to see a member's membership card. This may be your organization's official membership card or just a temporary one.

<div class="ui dividing header" id="users"><i class="hashtag icon"></i>Users</div>

This is where admins will manage user accounts. Admins can change the information of basically any user. The star besides a user name means that they are a staff member.

<img src="/assets/screenshots/1.0.0-alpha2/Screenshot_20180319_200937.png" class="ui image" />

You may add a new user by clicking on the Add User button. Make sure you set a password.

Find the user you are looking for and click in the blue Edit button. Change whatever you need to change. If the password is not being changed, leave it blank.

<div class="ui icon message">
  <i class="info circle icon"></i>
  <div class="content">
    <div class="header">About the password field in Users</div>
    The password field is there in preparation for the self service interface. Users will be able to put and change reservations on their own and a later release.
  </div>
</div>

<div class="ui dividing header" id="organizations"><i class="hashtag icon"></i>Organizations</div>

This is where admins will add new organizations. It works very similarly to the **Users** portion of Astral.

<div class="ui dividing header" id="organizations">
  <i class="hashtag icon"></i>
  <div class="content">
    Bulletin <span class="ui label"><i class="star icon"></i> New on 1.0.0-alpha2!</span>
  </div>
</div>

Bulletin is a feature added to help your non-profit communicate. It is nothing but a forum/message board. If you have used one before, it won't be hard to figure it out. Otherwise, the next items will show you how to use it.

<img src="/assets/screenshots/1.0.0-alpha2/Screenshot_20180319_201508.png" class="ui image" />

### Creating Posts

When you click on "Create New Post", you will be taken to the "Create Post" screen. Fill out the form according to your needs.

- Title: the title of your post, something that will describe it
- Category: what the post is about
- Sticky: if the post is important enough, it can stick to the top of the page
- Message: the content of the post. Text may be formatted using the message toolbar

<div class="ui icon message">
  <i class="info circle icon"></i>
  <div class="content">
    <div class="header">About new bulletin post categories</div>
    Make sure an administrator creates the bulletin post categories in Settings.
  </div>
</div>

### Editing Posts

If you need to edit a post your created, go to the post and click the Edit button, make the changes you need and click "Save".

<img src="/assets/screenshots/1.0.0-alpha2/Screenshot_20180319_201549.png" class="ui image" />

### Replying

To add a reply, wirte a message in the "Reply" box at the bottom of a post, after all the comments and click submit.

<div class="ui icon message">
  <i class="info circle icon"></i>
  <div class="content">
    <div class="header">About editing replies</div>
    As of 1.0.0-alpha2, it is not possible to edit post replies.
  </div>
</div>

### Announcements

At the main screen of bulletin you will see "Announcements" posts. Those are nothing morethan sticky posts.

If a post is important enough, you can make it an announcement by marking it as a sticky when you create or edit a post.

<div class="ui dividing header" id="settings"><i class="hashtag icon"></i>Settings</div>

This is where admins will set global values for the system.

<img src="/assets/screenshots/1.0.0-alpha2/Screenshot_20180319_201624.png" class="ui image" />

### General

In the General tab, admins will be able to set the name of the non-profit Astral serves and some other information on it, such as logo, cover picture, address and membership receipt text.

### Organizations

This is where you will set Organization types. The way you want to organize them is up to you. At the Mayborn Science Theater, we have an organization type for each independent school district.

### Tickets

The Tickets tab allows you to create Ticket Types for the system. You can allow tickets in more than one event type.

### Payments

System wide Payment types are set up here. Astral does not process payments online. Your Non-profit must have a way to process payments. This is just a way to "tag" the payments under a payment type.

### Events

Event types are set here. Event types are a classification/tag for an event. Is it a matinee? A school group? A weekend show? Normally, event types have different ticket prices.

### Users

This is where you set roles and whether or not a role is a "staff" role.

### Membership

This tab allows you to create membership types, set their prices and the duration of a membership.

### Bulletin

This tab allows you to configure bulletin settings.

<div class="ui dividing header" id="help"><i class="hashtag icon"></i>Settings</div>

The Help item takes you to this website where you will find the official documentation for Astral.
