---
title: Lunch & Learn
order: 4
image: lunch-learn.png
events:
- name: Vaidehi Joshi
  date: 2017-06-16
  time: "12:00 pm ET"
  title: Crafting Better Code Reviews
  description: We've probably all heard that peer code reviews can do wonders to a codebase. Many of us probably work on teams that (hopefully) have some kind of formal code review process. But is that enough? Motivated by own code review experiences, I've done some research on the different types of code review processes, and which ones are the most effective. Let's explore the history behind code reviews, and try and figure out what makes a strong code review, and what makes a painful one. By the end of this lunch and learn, you'll know not just the theory behind code reviews, but also how to put a good one into practice on your own team!
  twitter: vaidehijoshi
  #form: https://goo.gl/forms/wQFm1jbxhoPOUar02
- name: Stephanie Liu
  date: 2017-04-27
  time: "12:00 pm ET"
  title: Draggable Elements with Vanilla JS
  description: We'll be reviewing how to use vanilla JavaScript to create elements a user can drag with their mouse, [as seen in this demo](http://codepen.io/ramenhog/pen/gmGzRQ). After briefly touching on some significant user benefits of such UI, we will dive into understanding how to determine the position of a mouse click with mouse events and how to use that information to reposition the draggable element. *Some basic JavaScript knowledge will be required*.
  #form: https://goo.gl/forms/0M1oBRDfsSPrVPH62
  twitter: ramenhog
- name: Joni Trythall
  date: 2017-03-30
  time: "12:00 pm ET"
  title: SVGs from Illustrator to inline HTML
  description: This presentation will cover how to grab an SVG’s (Scalable Vector Graphics) code from Illustrator and add it to an HTML document, touch on the benefits of using it this way, and make note of how to prep these graphics for animation with CSS from the start.
  twitter: JoniTrythall
ad: Reach out to us at [hello@elaconf.com](mailto:hello@elaconf.com) to secure a Lunch & Learn sponsorship.
---

Each month the community will have the opportunity to sign up to attend a Google Hangouts presentation over lunch (12:00PM east coast time). The tone for these is casual, welcoming, and encouraging. The host is able to present for up to 30 minutes and determine whether they would like to take questions and where (live versus in the #lunchlearn channel as a follow-up).

These may also be recorded in the future if the host is comfortable with that as we understand not everyone has consistent or flexible lunch time each day.

### Upcoming and Past Lunch & Learns

<div class="events">
  {% assign lal = page.events | sort: 'date' %}
  {% for event in lal reversed %}
  <div class="event">
    <div style="background-image: url(/img/lunch-and-learn/{{event.name | slugify}}.jpg)" class="speaker-img-small event-img hide-small"></div>
    <div class="event-details">
      <div class="speaker-name"><strong>{{event.title}}</strong> by <a href="https://twitter.com/{{event.twitter}}">{{event.name}}</a></div>
      <div class="speaker-date small">{{event.date | date: "%B %d, %Y"}}{% if event.time %} {{event.time}}{% endif %}</div>
      <div class="speaker-description">
        {{event.description | markdownify}}
        {% if event.form %}<a href="{{event.form}}" class="button">Sign up</a>{% endif %}
      </div>
    </div>
  </div>
  {% endfor %}
</div>

### Hosting

If you are interested in hosting a Lunch & Learn [fill out a brief form](https://docs.google.com/a/elaconf.com/forms/d/e/1FAIpQLSfnpFqVMdUsdoQT-qOsKOx3wdGwh94T7qV8XAv5piW2PA7Prg/viewform) and we will be in touch!

### Attending

Each Lunch & Learn will have its own sign up form that will be shared in advance in Slack, on Twitter, and within the event details in the calendar.

Also, feel free to join the #lunchlearn channel in Slack to better capture questions that you may not get a chance to ask during the presentation.

### Sponsoring

We have opportunities for companies to sponsor these events, gaining recognition as a supporter with mentions of company name and logo on presentation promo materials, social media, and in our calendar. These funds also help secure any relevant books that would make for appropriate attendee giveaways for certain topics.

For those looking to really join and engage with the community we also offer the opportunity for a woman employee to host a Lunch & Learn. Please note that we require that presentations focus on sharing knowledge and experiences rather than direct company or product promotion; we’ll be posting more details about various partnership opportunities this month 🎁
