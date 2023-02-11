---
layout: page
title: DNB Hackathon
menu_title: Home
menu_icon: house-door
---

{:.secondary}
# {{ site.event_date }}, in association with the Digital Nasional Berhad
<!-- REMOVE THIS SECTION when you use this template -->
<div class="lead" markdown="1" style="color: #17479E;">
This hackathon is organized by [Digital Nasional Berhad](https://www.digital-nasional.com.my/),
for DNB Internal Staff.

</div>
<!-- END of section to remove -->

<div class="aside">
    <h2><i class="bi bi-calendar3" style="color: #17479E;"></i> Event timeline</h2>
    <dl>
        {% if site.registration_status == "soon" or site.registration_status == "open" or site.registration_status == "demo" %}
            <dt>{{ site.registration_opens_date }}</dt>
            <dd>
                Applications open for participants<br>
                {% if site.registration_status == 'open' %}
                    <a href="{{ site.baseurl }}{% link registration.md %}" class="btn">Register now</a>
                {% elsif site.registration_status == 'closed' %}
                    <a class="btn disabled">Registration has closed</a>
                {% elsif site.registration_status == 'soon' %}
                    <a class="btn disabled">Registration opens soon</a>
                {% endif %}
            </dd>
        {% endif %}

        <dt>{{ site.registration_closes_date }}</dt>
        <dd>Applications close</dd>

        <dt>{{ site.event_date }}</dt>
        <dd>Hackathon date</dd>
    </dl>
</div>

{% if site.event_status != "over" %}

Researchers from Digital Nasional Berhad hosted a 15-day hackathon on
{{ site.event_date }}, open to students, to...

Students can sign up to [topics ranging from]({{ site.baseurl }}{% link projects.md %})
... to ..., and more. Students could sign up to [topics ranging from]({{ site.baseurl }}{% link projects.md %})
... to ..., and more. Participating members could be from any Malaysia academic institution.
Students can register at [registration page]({{ site.baseurl }}{% link registration.md %}).


Participation is open to **students from any Malaysia academic institution**.

## Logistics

The event will take place virtually, using a combination of **video
conferencing** (Zoom) for meetings and seminars, and **discussion forums**
(Slack) for ongoing comms. Data holding and analysis will take place on...

## Prizes

<ul class="grid">
    <li class="project">
      <h3> First Prize</h3>
      <a href="{{ site.baseurl }}/"><img src="{{ site.baseurl }}/assets/first.jfif"/></a>
      <h3> Samsung S73 </h3>
    </li>
    <li class="project">
      <h3> First Prize</h3>
      <a href="{{ site.baseurl }}/"><img src="{{ site.baseurl }}/assets/second.jfif"/></a>
      <h3> Realme Pad X </h3>
    </li>
    <li class="project">
      <h3> First Prize</h3>
      <a href="{{ site.baseurl }}/"><img src="{{ site.baseurl }}/assets/third.jfif"/></a>
      <h3> Samsung A23 </h3>
    </li>

</ul>

[faq]: {{ site.baseurl }}{% link faq.md %}

{% else %}

Thanks for the participation. See you in upcoming hackathon events.

{% endif %}
