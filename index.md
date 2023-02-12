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
<img src="{{ site.baseurl }}/images/leadingimages.jpg">
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

## Prizes for Top 3 Teams

<u2 class="grid">

<li class="imag" markdown="1">
{% include imagedisplay.html title="First Prize" image="first.jpg" %}

<p><b>Samsung Galaxy A73 5G</b></p>
<p>(RRP: RM 2099)</p>
</li>

<li class="imag" markdown="1">
{% include imagedisplay.html title="Second Prize" image="second.jpg" %}

<p><b>Realme Pad X</b></p>
<p>(RRP: RM 1699)</p>
</li>

<li class="imag" markdown="1">
{% include imagedisplay.html title="Third Prize" image="third.jpg" %}

<p><b>Samsung Galaxy A23 5G</b></p>
<p>(RRP: RM 999)</p>
</li>

</u2>

<main class="page-content" aria-label="Content" style="background: white; font-family: 'Open Sans', 'Helvetica Neue', Helvetica, Arial, sans-serif; color: black;">      
<div class="wrapper">
<p>Form your squad up to a maximum of 4 members right now and</p>
<p><b>stand a chance to win these amazing prizes!</b></p>

[Join now and form your team](https://forms.office.com/Pages/ResponsePage.aspx?id=VUIF41YjAU2H6BEeteoS4LGYf9e_wDFGo65PpU1kp0pUMFJHMVROTlZWQ1IwMVlNWTlJWUhaRE83Ty4u){:.btn target="_blank"}

[Submit your Work Here](https://digitalnasionalberhad-my.sharepoint.com/:f:/g/personal/mani_kagita_digital-nasional_com_my/ElranH5gA49Fk5Nll3-EL-cB9lGyHqo-Ln38v08fA2xwOg){:.btn target="_blank"}

[faq]: {{ site.baseurl }}{% link faq.md %}

{% else %}

Thanks for the participation. See you in upcoming hackathon events.

{% endif %}

</div>
</main>