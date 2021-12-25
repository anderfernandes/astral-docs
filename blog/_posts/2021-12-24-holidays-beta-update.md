---
layout: post
title: Holidays beta update!
permalink: /:categories/:title
date: 2021-12-24 9:42:32 -0500
categories: updates
cover: https://cdn.pixabay.com/photo/2019/12/09/17/49/merry-4684006_960_720.jpg
excerpt: Hello everyone! 2020 was the most challenging year for our generation, and things were not different with me.
---

<img src="https://cdn.pixabay.com/photo/2019/12/09/17/49/merry-4684006_960_720.jpg" class="ui image" />

So... Here we are. The end of 2021. It's hard to believe how fast we got here.

This was the most defining year of my life with some huge challenges that I was able to overcome
with a lot of determination. The battle to make the world a better place continues! I have finally
reached a point where I can focus more time on Astral!

This year I have experimented a lot with manu user interface technologies to figure out which one
would best fit my style, the application, the kind of user and developer experience I want for this
project. I must say that the experimenting has took way longer than expected, but I have finally
found the best choice and now, it's all a matter of moving foward.

I have picked a date for beta zero pre-release: **February 15, 2022**. In this release, you will be able to:

- Login to a "public" portal with events, calendars and show library
- Create, read and update users, events, shows, sales
- Sell tickets in Cashier
- Change global settings

This will be a very minimum test release focused only on features for staff member. However, I am
confident that once I get there, moving forward will be a breeze. Now, on to a little bit of what's
to come! Here is how you will create events:

## Revamped Event Form

<video autoplay loop>
  <source src="/assets/videos/2021-12-24_17-00-18.mp4">
</video>

On this first one, there's a lot going on. A lot has changed! You can see how the colors are basically
the same and the feel is familiar, but there's definetely an update to the look, feel and user experience
of the application and that's what I worked on all year. In fact, that's why rewriting Astral is taking
longer than I expected.

There's a preview on the left side which allows you to see the data of the event you're trying to create.
It's there the entire time (except on mobile). Also, the data automatically updates as you change it.
On the left you have buttons with "actions". The entire application is going to have this layout on
desktop and tablets. On mobile, those sidebars will be hidden and only what's in the center will stay.

I have created a basic Matinee and limited the number of available seats, something a lot of science
centers have to do now because of the pandemic.

## Validation

<video autoplay loop>
  <source src="/assets/videos/2021-12-24_17-02-27.mp4">
</video>

As you are creating events, I've noticed how easy it is to make mistakes. That's why validation
happens as you enter data. In the exemple above I was trying to change the end date of the event
for an invalid date and it correctly told me that I coudln't.

## Multiple Events

<video autoplay loop>
  <source src="/assets/videos/2021-12-24_17-06-34.mp4">
</video>

Sometimes you have to create events for the whole week, or the whole month. Astral can do that,
as long as you don't create more than 25 at a time. This number might change, but I chose to limit
it so that we don't overload the application. In addition, if there's at least one thing in any of
the events it is not expecting, it wil not save ANY event.

<video autoplay loop>
  <source src="/assets/videos/2021-12-24_17-09-18.mp4">
</video>

Notice how we can select one event or the other, and even delete events in case you change your mind
while creating them. When a second event is added, it copies the data of some of the most common fields
if you are creating multiple events. In this case, it adds one hour to the start and ending times of
each event and doesn't change the event type. Pretty handy!

## All Day Events

<video autoplay loop>
  <source src="/assets/videos/2021-12-24_17-13-48.mp4">
</video>

Sometimes you need to create events that will be "at the top" of your Calendar, events that will last
all day or just something that will serve as a placeholder, for example, for maintenance. This is
why you would create an all day event. In the example above I created a Staff Metting.

## Multiple All Day Events

<video autoplay loop>
  <source src="/assets/videos/2021-12-24_17-16-51.mp4">
</video>

In case you want to create multiple all day events, that is also possible.

## All Day Event Validation

Last but not least, all day events are also validated.

<video autoplay loop>
  <source src="/assets/videos/2021-12-24_17-18-11.mp4">
</video>

<hr />

This is defintely the most used part of the application. That's where everything starts and it's
only fair that I start here as well. There are a few more features I want to add to this part of
the app, but for the most part for now I'll just make sure it is smooth. I am sure you will find
working with this new way of creating events very pleasant!

I am looking forward to show you more features, specially the cashier side of things. I have experimented
with it and was able to get pretty close to what I've always wanted it to be. I am sure your cashiers
will find it pleasant as well. Look forward ot that. In the meantime, happy holidays to you and your loved ones! Thank you for reading!
