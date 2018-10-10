---
layout: post
title:  "State of alpha3"
permalink: /:categories/:title
date:   2018-10-10 12:09:22 -0500
categories: alpha3
cover: https://i.imgur.com/lyNGgY1.png
excerpt: Alpha3 has been quietily out due to a lot of work.
---

Hello, everyone!

I know I haven't been writing a lot, but alpha-3 has been in use in production since September 1st, 2018.
Our staff praised it highly and there were some new challenges with this release. Fortunately,
we overcame all of them.

After pushing alpha3 to production we added more features and fixed all the bugs we found. Now,
I am glad to announce that this release is finally worth talking about.

Besides the new calendar features and sales interface, we have added minor changes that will make
the life of our users easier:

- You can now browser to a particular month with a mini calendar widget instead of browsing to
a date way in the future manually
<img src="https://i.imgur.com/lyNGgY1.png" class="ui image">

- Several assets managed by Astral can now be active or inactive, which will determine wheter or
not they will be available to consume.
<img src="https://i.imgur.com/QeqZGdV.png" class="ui image">

- Users can now create and edit their own show types.
<img src="https://i.imgur.com/P5iXnro.png" class="ui image">

- Ticket types may now be public or private. This will help us in the future when Astral is serves
its REST API (yes, I've never talked about it, but we do have it) to fetch things like upcoming
public and private shows
- You may now sell products only if you want
- Password recovery via email
- Email delivery confirmation

There you have it. Now, the question that remains unanswered: where are we going from here?

Starting next week, I am going to start working on the self service area of Astral. Your visitors
will be able to go get their own tickets and make their own reservations. The plan is to start
serving teachers, groups and members since those are  the vast majority of our visitors. I am very
excited for this portion of the project! I will see you on the next one!
