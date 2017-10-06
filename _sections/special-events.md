---
title: Special Events
order: 6
events:
- name: Breanna O'Brien
  date: 2017-06-06
  time: "3:30 pm ET"
  title: A remove Q & A with Breanna O'Brien
  description: 'Brenna O’Brien is a professional coach for tech conference speakers and a front-end engineer at TED. Committed to increasing diversity in tech and building healthier developer communities, Brenna is a volunteer instructor for Ladies Learning Code, founder of NodeSchool Toronto, and a former bootcamp instructor for HackerYou. She has also spoken extensively about creative coding, developer culture, and navigating the tech industry as a beginner.<br><br><strong>Topics:</strong> Finding conferences to submit to, Writing a great proposal, Talk preparation, Feedback on talk rehearsals, Navigating conference speaking as part of a marginalized group, Negotiating compensation, Pep-talks and encouragement, What to wear on stage. Anything public speaking related is fair game!'
  twitter: brnnbrn
  #form: https://goo.gl/forms/LyfNdbs845LceEnD2
---

<div class="events">
  {% assign ama = page.events | sort: 'date' %}
  {% for event in ama reversed %}
  <div class="event">
    <div style="background-image: url(/img/special-events/{{event.name | slugify}}.jpg)" class="speaker-img-small event-img  hide-small"></div>
    <div class="event-details">
      <a href="https://twitter.com/{{event.twitter}}" class="speaker-name">{{event.name}}</a>
      <div class="speaker-date small">{{event.date | date: "%B %d, %Y"}}{% if event.time %} {{event.time}}{% endif %}</div>
      <div class="speaker-description">{{event.description | markdownify}}</div>
      {% if event.form %}<a href="{{event.form}}" class="button">Sign up</a>{% endif %}
    </div>
  </div>
  {% endfor %}
</div>
