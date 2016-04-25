---
layout: page
title: About Us
permalink: /about/
css: about.css
---

Comedy Society at the University of York provides a platform for all people to do all types of comedy.
We host shows every week of term, all completely written and performed by our members. As well as this we run weekly workshops on <span class="red">Stand Up, Writing and Improv.</span> All of our workshops give you the chance to try out your ideas or get inspiration from others in a <span class="red">pressure free</span> environment.

We also go to the Edinburgh Fringe every year in the form of two shows; our sketch show, [Present & Correct](http://www.nouse.co.uk/2015/08/15/edinburgh-fringe-2015-review-present-and-correct/) and our Improv show, [The Shambles]({{site.shambles_website}}).

<h3 class="red">I want get involved!</h3>
Fantastic! The easiest way to get involved is to join our mailing list by emailing [comedysoc@yusu.org](mailto:comedysoc@yusu.org). We also have our own Facebook group which you can join [here.](https://www.facebook.com/groups/1713862662184771/?fref=ts) Keep an eye on our weekly emails to see the times and locations of our workshops as they can change.

Details for our workshops are listed as follows:

{% for workshop in site.data.workshops %}
- <h5 class="red">{{ workshop.name }}</h5>
  - [Facebook Group]({{ workshop.group-link}})
  - <span class="red">Where:</span> {{ workshop.location }}
  - <span class="red">When:</span> {{ workshop.datetimestring }}
{% endfor %}


All of our workshops are free to attend however, if you'd like to perform in one of our shows, you'll have to pay our low membership fee of <span class="red">£5!</span> You can pay membership [here.](https://www.yusu.org/opportunities/societies/comedy-society)
