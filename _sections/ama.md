---
title: AMA
order: 3
events:
- name: Molly Sheehan
  date: 2017-05-09
  time: '12:00 pm ET'
  description: Molly Sheehan is a bioengineering postdoctoral fellow running for US Congress.
  twitter: pennsymolly
- name: Jill Jubinski
  date: 2017-04-11
  time: '12:00 pm ET'
  description: Recruiting veteran and community manager. Chat about career growth and direction, salary negotiations, mentorships, and more.
  twitter: jilljubs
- name: Lara Hogan
  date: 2017-03-15
  time: '12:00 pm ET'
  description: Engineering Director at Etsy, author of *Demystifying Public Speaking* and *Designing for Performance*.
  twitter: lara_hogan
- name: Una Kravets
  date: 2017-01-31
  description: UI engineer at DigitalOcean and co-host of Toolsday.
  twitter: Una
ad: Reach out to us at [hello@elaconf.com](mailto:hello@elaconf.com) to secure an AMA sponsorship.
---

We’ll be hosting a monthly “ask me anything” series in our Slack channel, #ama. These sessions will take place on designated weekdays either around 12PM EST or 6:30PM EST and last up to one hour, depending on the guest’s schedule.

Our goal here to to provide designated time to seek advice and support from peers related to work, communication, community, and technology. Everyone has a unique story and perspective to share and getting to know one another better can be educational and go a long way in feeling truly part of something. Through our mission we are dedicated to creating a welcoming, inclusive space for women in tech to learn from and empower one another and part of that is providing a platform to ask questions.

We also envision this being a great opportunity to speak directly with employees of tech companies that are looking to hire, gaining valuable insider knowledge and preferences.

All guests this year will receive a complimentary ticket to Ela Conf 2017 🤗

### How it Works

Guests will receive an invite to the Slack channel prior to the start of the #ama. Guests are asked to send along a short bio to organizers sharing their background and mentioning any specific work or projects they would be especially excited to talk about right now. Bios will be shared in #general in the time leading up to the event and used to promote the ama on Twitter.

Each session will begin with an introduction and shared bio on behalf of the organizers, followed by the start of participant questions. Guests will choose and answer questions until the established end time, though it may not be possible to touch on every submitted question. Following a [threaded discussion format](https://slackhq.com/threaded-messaging-comes-to-slack-417ffba054bd#.t88f3budk), participants are free to ask any follow-up questions they may have as well.

If as a participant you find yourself unable to attend a scheduled #ama please feel free to pass along your questions to an organizer before the event.

### Upcoming and Past AMAs

Do you know someone who would be great as an AMA guest? Or would you like to recommend yourself? Fill out our [AMA Suggestion Box form](https://goo.gl/forms/i0QOjNupmO9e9hWA3).

<div class="events">
  {% assign ama = page.events | sort: 'date' %}
  {% for event in ama reversed %}
  <div class="event">
    <div style="background-image: url(/img/ama/{{event.name | slugify}}.jpg)" class="speaker-img-small event-img  hide-small"></div>
    <div class="event-details">
      <a href="https://twitter.com/{{event.twitter}}" class="speaker-name">{{event.name}}</a>
      <div class="speaker-date small">{{event.date | date: "%B %d, %Y"}}{% if event.time %} {{event.time}}{% endif %}</div>
      <div class="speaker-description">{{event.description | markdownify}}</div>
    </div>
  </div>
  {% endfor %}
</div>

### To Join

* As an existing Ela Slack member simply search for and join the #ama channel
* As a non member [please complete a brief form](https://docs.google.com/forms/d/e/1FAIpQLSctRXPSgQaXHkawUB2gP8NR0w41KsAbZit8AZr4q19swxQ50A/viewform) to receive an invite to our Slack; welcome!

*Friendly reminder that the Ela community, including Slack, is for adult women (18+).*

### Rules and General Guidelines

As with all Ela related activities it’s essential that all participants follow [our code of conduct](http://elaconf.com/code-of-conduct).

### Sponsoring

We have opportunities for companies to sponsor these events, gaining recognition as a supporter with mentions of company name and logo on presentation promo materials, social media, and in our calendar. These funds also help secure any relevant books that would make for appropriate attendee giveaways for certain topics.

For those looking to really join and engage with the community we also offer the opportunity for a woman employee to host an AMA. Please note that we require that presentations focus on sharing knowledge and experiences rather than direct company or product promotion; we’ll be posting more details about various partnership opportunities this month 🎁
