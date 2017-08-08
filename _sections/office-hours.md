---
title: Office Hours
order: 5
image: office-hours.png
hosts:
- name: Lara Hogan
  topics: Being a manager, public speaking fears and tips, and navigating being part of an underrepresented group in tech
  description: Engineering Director at Etsy, author of *Demystifying Public Speaking* and *Designing for Performance*
  twitter: lara_hogan
- name: Julia Elman
  topics: Tech for good, being a working mom in tech, people management, building design systems
  description: Design manager at Zapier, co-author of Lightweight Django, WERK MAMA.
  twitter: juliaelman
---

The Ela #office-hours channel serves as a designated space for community members to connect directly with scheduled hosts to ask career related questions, get advice, and seek general support during publicized times.

Hosts can choose to have ongoing availability with set times, more sporadic availability, or choose to participate in a one-time, scheduled occurrence. Each host will post and maintain their availability, pinning to the #office-hours channel for quick reference.

### Current hosts

<div class="events">
  {% assign hosts = page.hosts | sort: 'date' %}
  {% for event in hosts reversed %}
  <div class="event">
    <div style="background-image: url(/img/office-hours/{{event.name | slugify}}.jpg)" class="speaker-img-small event-img  hide-small"></div>
    <div class="event-details">
      <a href="https://twitter.com/{{event.twitter}}" class="speaker-name">{{event.name}}</a>
      <div class="speaker-description">{{event.description | markdownify}}</div>
      <div class="speaker-topics">Suggested topics: {{event.topics}}</div>
    </div>
  </div>
  {% endfor %}
</div>
