---
layout: post
published: true
title: Foreign Data Wrappers Accessing External Data from a PostgreSQL database
modified: 2020-03-03 13:06:41
categories: articles
author: doug_hunley
tags:
  - pgcmh
  - postgresql
comments: true
share: true
---

What
----

The March meeting will be held at **18:00 EST on Tues, the 24<sup>th</sup>**. Once again, we will be holding the meeting in the community space at CoverMyMeds. *Please RSVP on [MeetUp](https://www.meetup.com/postgresCMH/events/bjbmcmybcfbgc/) so we have an idea on the amount of food needed.*

Foreign data wrappers are part of Postgres's implementation of the SQL/MED (Management of External Data) extension to the SQL standard, which provides the specs for accessing data that's not actually in your database.

This might sound stuffy and boring, but it's not! If you're managing multiple datastores and want to Just Use Postgres, foreign data wrappers are a good option. There are loads of them available, for nearly every datastore you can think of, and you can write your own if you can't find what you're looking for.

This mostly-demo talk showcases file_fdw, which allows you to query local resources from your database, and postgres_fdw, which allows you to query other PostgreSQL databases. Gabrielle will cover use (and mis-use) cases, the configuration of each, and interesting quirks.

Familiarity with psql is helpful but not required for this all-levels talk.

Gabrielle Roth has been using Postgres since sometime in the version 7s, and thinks that the best part of using Open Source software is the culture of sharing knowledge. She's a Senior Data Engineer at NS1 and co-founder and former co-lead of PDXPUG.


Where
-----

CoverMyMeds has graciously agreed to validate your parking if you use their garage so please park there:

<iframe src="https://www.google.com/maps/embed?pb=!1m0!3m2!1sen!2sus!4v1488389756992!6m8!1m7!1sLjB1moOcFPJm5UT4cdhnig!2m2!1d39.95415440342131!2d-83.0050335305906!3f321.1273220824533!4f-4.543767100369678!5f0.7820865974627469" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>

 **You can safely ignore any sign saying to not park in the garage as long as it's after 17:30 when you arrive.**

_Park in any space that is not marked '24 hour reserved'._

Once parked, take the elevator/stairs to the 3<sup>rd</sup> floor to reach the Miranova lobby. Once in the lobby, the elevator bank is in the back (West side) of the building. Take a left and walk down the hall until you see the elevator bank on your right. Grab an elevator up to the 11<sup>th</sup> floor. _(If the elevator won't let you pick the 11<sup>th</sup> floor, contact Doug or CJ (info below))._ Once you exit the elevator, look to your left and right; one side will have visible cubicles, the other won't. Head to the side _without cubicles_. You're now in the community space:

![Community space as seen from the stage](https://www.scriptscribe.org/wp-content/uploads/2015/12/Hour-of-code-2.jpg)

The kitchen is to your right (grab yourself a drink) and the meeting will be held to your left. Walk down the room towards the stage.

**If you have any issues or questions with parking or the elevators, feel free to text/call Doug at +1.614.316.5079 or CJ at +1.740.407.7043**
