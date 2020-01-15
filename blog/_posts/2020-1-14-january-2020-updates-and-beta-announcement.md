---
layout: post
title:  January 2020 updates and beta announcement!
permalink: /:categories/:title
date:   2020-1-14 21:10:10 -0500
categories: alpha4
cover: /assets/images/Screenshot_20200114_210030.png
excerpt: Easily create memberships, better membership management, automated emails and much more! Also, our better will arrive in the second quarter of 2020!
---

In 2019, Astral received many updates and improvements, but none of them made 
me as proud as the ones I released at the end of the year: A full rework of
cashier as well as a membership wizard and automated email alerts for field trip
confirmations. Somehow, these new features were challenging and fun to work on 
at the same time and I am not really sure why I feel that way. However, I would 
defintely say that the best part of this project is still coming.

In this blog post I plan on introducing two new features: the "New Membership
Wizard" and automated email alerts for upcoming field trips.

## New Membership Wizard

Back in the 90's I remember using "wizards" in Microsoft Office to get certain
things done because all I had to do is give it data and it would do what I needed
it to do. When I was approached to simplify the way memberships are created, I 
almost instantly thought of creating a wizard. Let's take a look!

After you login into Admin, go to Members and click the "New Member Wizard" button.

<img src="/assets/images/Screenshot_20200114_213730.png" class="ui image" />

<img src="/assets/images/Screenshot_20200114_210030.png" class="ui image" />

The wizard is split into four parts:

**1. Primary**

In this step, the wizard will ask for information on the primary user. **After you
enter the email of the primary membership holder, Astral will check if that email
is already associated with an user account**. If there is, Astral will use that
user as the primary in the membership and there will be no need to enter their
information. 

<img src="/assets/images/Screenshot_20200114_215006.png" class="ui image" />

If that email is new, you will be required to enter user information
such as address and phone number so that at the end of the process, a user account for
the primary can be created along with the membership at the end of the wizard.

<img src="/assets/images/Screenshot_20200114_215248.png" class="ui image" />

Click on the "next" button to go to the next step. **It will appear only when you enter
valid data in each of the fields**. Double check the information entered if it doesn't appear.

**2. Details**

In this step you will select which membership package that member wants. These 
come from Settings. Whatever membership packages you have there are going to be
listed here. Select which one the prospect member wants by clicking in one of them.
Next, select the start date of the membership. You can select a different date
for the end date of the membership, but by default, will follow the following
formula: start date = start date + duration. You can see that the duration of
the memberships is 365 days. The default end date for the memberhsip will be
365 days in the future from the start date selected.

<img src="/assets/images/Screenshot_20200114_220030.png" class="ui image" />

Note how each membership package option shows all of its benefits, including
number of free secondaries, as well as price and length.

Click on the "next" button to go to the next step.

**3. Secondaries**

In this step, you will enter free and non free secondaries if necessary. Astral
will make sure that you add all possible free secondaries before you start adding
non free secondaries for the membership. Not adding secondaries is also okay.
Again, Astral will check the emails to see if they are not associated with any
user accounts. If they already exist in the database, you won't have to enter
any of their information.

<img src="/assets/images/Screenshot_20200114_220840.png" class="ui image" />

One big thing I did see very common is that many secondary members had the same
address as the primary. In order to speed things up you can check the box below
the for for each secondary to use the primary's address and phone so that you
don't have to type it again in case it's the same.

You will be allowed to add only the permited number of free secondaries. There
are no limit to the number of secondaries. It is up to your science center to
figure out if you want to limit that or not.

You can add as many secondaries as you want on this screen. Their user accounts
will be created at the end of the wizard if they don't exist.

**4. Payment**

It is now time for the customer to pay for the membership. This screen will
show the totals, including tax and each non free secondary added and calculate
automatically. Enter the customer's payment information and you are all good.

<img src="/assets/images/Screenshot_20200115_130813.png" class="ui image" />

The next screen will show you all the data the wizard gathered. You may go back
to any step to fix anything or add anything you might have missed. Make sure
you got everything right. **At this point, nothing (user accounts, memberships, 
sales, payments) has been created** but it will be once you click the confirm 
button on the confirmation screen.

<img src="/assets/images/Screenshot_20200115_131356.png" class="ui image" />

An done!!! A membership, as well as user accounts, sales and payments have been
created, just like that!

<img src="/assets/images/Screenshot_20200115_135413.png" class="ui image" />

<div class="ui divider"></div>

Long story short, here's what you can do with the New Member Wizard:

- Define a primary
- Select a membership option
- Define free and non free secondaries, based on the rules for each membership option
- Membership payment
- Astral will check all emails entered for primaries and secondaries. If the 
email is already associated with an account, Astral will use the information it
already has. Otherwise, the person creating the membership will have to enter that
information manually
- For secondaries, both free and non free, the person creating the membership
can use the primary's address information by checking the box below the form
- No user accounts, sales, memberships or payments are created until the confirmation
screen is shown

## Automated email alerts for upcoming field trips

After the Mayborn Science Theater switched to Astral, the demand for field trips
increased in a way we were not expecting. This growth caused problems when
we had to confirm field trips. With most of the staff being part timers, it was
hard to confirm all the field trips because someone has to call and since we are
dealing with teachers, they may be in classroom during business hours. In order
to solve this problem, I made it so that teachers can confirm their own reservation
via email. If your instance of Astral has been updated today or later, you will
have this feature. Also, if you can't see items shown in the next few screenshots,
that means that your installation is not capable of this feature. Please update
to get it to work. Also, email sending should be properly configured.

In order to have automated email alerts for upcoming field trips to work, the
first thing you need to do is go to Settings / General / Self Confirmaton Settings
and enable it. Select how many days before each field trip the group leader on record 
will get the email.

<img src="/assets/images/Screenshot_20200115_135654.png" class="ui image" />

Once you set it up, once a day, at the time you set, Astral will go through all
sales that have events going on in whatever amount of days you have set and email
the group leader responsible for them. In the case of the screenshot above, Astral
will email all field trips that are happening in the next 7 days, at 7:30 AM.

One important thing to mention is that **the group leader will keep getting the
automated email until the sale is marked as confirmed**. Hopefully the email won't
go to their spam folder. We are hoping that they confirm it themselves or call your
science center to make changes and confirm.

After enabling the self confirmation alerts, the work flow is pretty simple:

- Group Leader will get an email that will ask them to confirm their field trip:

<img src="/assets/images/Screenshot_20200115_150341.png" class="ui image" />

- When they click on the link, their browser will show a page in which they will
be able to confirm their field trip. This is a unique link that only the group
leader will have. The link already logs the group leader and gives them access to
see their own reservation. If everything looks good, they should click confirm at
the bottom of the page, which is also optimized for mobile devices.

<img src="/assets/images/Screenshot_20200115_150509.png" class="ui image" />

<img src="/assets/images/Screenshot_20200115_150630.png" class="ui image" />

- After confirming their own reservation, the group leader will get a confirmation
letter on their email. The user who created the sale will get one as well.

<img src="/assets/images/Screenshot_20200115_150630.png" class="ui image" />

The self confirmation process also adds memos when it sends the emails and
when the reservation has been confirmed. The first one is a system memo and the
second will have the group leader's name.

<img src="/assets/images/Screenshot_20200115_153115.png" class="ui image" />

That's it!

## Beta announcement

At this point, Astral accomplishes many things, but not everything I have envisioned.
In order to get closer to that vision, we are going to recreate the entire application
using better coding standards, newer technologies and a new but familiar user
interface. In order to do that, we will start from scratch. The first beta of
Astral will do everything it does up to this point, but better, faster and prettier.
We are looking to have our first beta out sometime during the second quarter of 2020.
I will be posting some of the progress here so don't miss out. 

See you next time!
