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

<div class="aside" style="color: #17479E;">
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

        <dt>{{ site.submission_date }}</dt>
        <dd>Submission date</dd>

        <dt>{{ site.result_date }}</dt>
        <dd>Results Announcement</dd>
    </dl>
</div>


<div class="page-content" aria-label="Content" style="background: white; font-family: 'Open Sans', 'Helvetica Neue', Helvetica, Arial, sans-serif; text-align: justify; text-justify: inter-word; color: #159957;">
<section>
<div class="wrapper">
<p style="font: 20px;"><b> Rules for joining the DNB Hackathon</b></p>
<p>1.	All team members have to be on the DNB payroll (permanent or contractor).</p>
<p>2.	If you want you can join more than one team, but in case multiple teams you are a member of get a price then be aware that you only get one price.</p>
<p>3.	When the team you are a member of has selected their problem statement do make sure that this information is added to the team information stored in the system being part of the DNB Hackathon programme.</p>
<p>4.	Teams obtaining first, second or third place only get a price.</p>
<p>5.	A 5 member Jury (50% external and 50% internal) will decide on the 10 teams having to present for the Jury and the subsequent teams one, two and three.</p>
<p>6.	Your proposed solution must be on slides (Powerpoint) with max of 8 slides (excluding cover slide).</p>
<p>7.	Do make sure that your solution is loaded before the DNB Hackathon deadline; If not then your solution will be excluded.</p>

</div>
</section>
</div>

  

<p></p>
<p></p>
<p style="font: 20px; text-align: center;">Form your squad up to a maximum of 4 members right now and</p>
<p><b>stand a chance to win these amazing prizes!</b></p>

<button class="favorite styled" type="button" formation="https://forms.office.com/Pages/ResponsePage.aspx?id=VUIF41YjAU2H6BEeteoS4LGYf9e_wDFGo65PpU1kp0pUMFJHMVROTlZWQ1IwMVlNWTlJWUhaRE83Ty4u">
    Join now and form your team
</button>


[Submit your Work Here](https://digitalnasionalberhad-my.sharepoint.com/:f:/g/personal/mani_kagita_digital-nasional_com_my/ElranH5gA49Fk5Nll3-EL-cB9lGyHqo-Ln38v08fA2xwOg){:.btn target="_blank"}

[faq]: {{ site.baseurl }}{% link faq.md %}


  
<div class="page-content" aria-label="Content" style="background: white; font-family: 'Open Sans', 'Helvetica Neue', Helvetica, Arial, sans-serif; color: #159957;">
<section>
<div class="wrapper">
<p><b> Prizes for Top 3 Teams</b></p>
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

</div>
</section>
</div>

