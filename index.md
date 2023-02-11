---
layout: page
title: Digital Hackathon
menu_title: Home
menu_icon: house-door
---

{:.secondary}
# {{ site.event_date }}, in association with the Digital Nasional Berhad
<!-- REMOVE THIS SECTION when you use this template -->
<div class="lead" markdown="1">
This hackathon is organized by [Digital Nasional Berhad](https://www.digital-nasional.com.my/),
for Malaysia University Students.

For more information: view the [README](https://github.com/manikumarkagita/hackathon/blob/main/README.md) 
or the [GitHub repository](https://github.com/manikumarkagita/hackathon).
</div>
<!-- END of section to remove -->

<div class="aside">
    <h2><i class="bi bi-calendar3"></i> Event timeline</h2>
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

## Outputs

By the end of the event, we hope to...

[faq]: {{ site.baseurl }}{% link faq.md %}

{% else %}

Researchers from Digital Nasional Berhad hosted a 15-day hackathon on
{{ site.event_date }}, open to Malaysia University Students, to...

Students could sign up to [topics ranging from]({{ site.baseurl }}{% link projects.md %})
... to ..., and more. Participating members could be
from any Malaysia academic institution.

The event took place virtually, using a combination of **video conferencing**
(Zoom) for meetings and seminars, and **discussion forums** (Slack) for ongoing
comms. Data holding and analysis took place on...

{% endif %}
