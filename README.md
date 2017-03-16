# Ela Community [![Build Status](https://travis-ci.org/elaconf/ela.community.svg)](https://travis-ci.org/elaconf/ela.community)

Ela Conference works to eliminate the existing diversity gap in tech by empowering more individuals identifying as a woman (18+) in a way that is significant to them to be leaders and take action through practical training and thoughtful mentorships.

## Build

This site is built with [Jekyll](http://jekyllrb.com/), see [Using Jekyll with Pages](https://help.github.com/articles/using-jekyll-with-pages/) for more information about installing and running Jekyll.

Recommended build: `bundle exec jekyll serve -w`

To run tests locally. The tests lint the SCSS and HTML:

```
npm install
npm test
```

Notes:

* Content for each section of the site is located in `_sections/` folder.
* The intro text lives in `index.html`

## Add a new AMA, Lunch & Learn, or Office Hours host

1. Open the page's markdown file, for example `_sections/ama.md`.
2. In the header of the page add to `events:` or `hosts:`

```yaml
- name: # Name of the host or speaker
  date: # Date of the event in YYYY-MM-DD format
  title: # (For Lunch & Learn only) title of the talk
  description: # One sentence bio of the host
  twitter: # Twitter handle of the host
  topics: # (For Office Hours only) List of suggested topics for the host's office hours
```
