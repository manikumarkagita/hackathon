---
title: Hackathon registration
menu_title: Registration
menu_icon: clipboard-check
event_status:
 - soon
---

{:.lead style="color: #17479E;"}
Participation is open to researchers from any Malaysia academic institution. {% if site.registration_status
== "soon" or site.registration_status == "demo" %}Registration opens on
{{ site.registration_opens_date }}.{% endif %} The closing date for applications
is {{ site.registration_closes_date }}.

<div class="aside" markdown="1" style="color: #17479E;>
This virtual event will require some commitment prior to and including the
Hackathon Event which will take part from {{ site.event_date }}.

{% if site.registration_status == "soon" or site.registration_status == "demo" %}
  <a class="btn disabled">Registration opens soon</a>
{% endif %}
{% if site.registration_status == "open" or site.registration_status == "demo" %}
  [Complete the application form](https://forms.office.com/Pages/ResponsePage.aspx?id=VUIF41YjAU2H6BEeteoS4LGYf9e_wDFGo65PpU1kp0pUMFJHMVROTlZWQ1IwMVlNWTlJWUhaRE83Ty4u){:.btn target="_blank"}
{% endif %}
{% if site.registration_status == "closed" or site.registration_status == "demo" %}
  <a class="btn disabled">Registration has closed</a>
{% endif %}

The closing date for applications is {{ site.registration_closes_date }}.
</div>

We are looking for enthusiastic and dedicated researchers who already have
experience with analysing ... data, and who are keen to experience working with
different scientists and institutes, and perhaps on topics not immediately in
their area.  

This virtual event will require approximately two hours commitment prior to the
hackathon, and then 15 days commitment during the event, which will take part
from **{{ site.event_date }}**. Technical support and guidance will be provided
by the [Digital Nasional Berhad](https://www.digital-nasional.com.my/), but we 
expect all applicants to have prior knowledge of technological concepts.


The closing date for the applications is {{ site.registration_closes_date }}. If
you have any queries, or have any difficulties completing the registration form,
please email our dedicated mailbox: <{{ site.mailbox_address }}>.

[faq]: {{ site.baseurl }}{% link faq.md %}
