---
layout: page
title: DNB Hackathon
menu_title: Home
menu_icon: house-door
---

{:.secondary}
# {{ site.event_date }}
<a href="https://forms.office.com/Pages/ResponsePage.aspx?id=VUIF41YjAU2H6BEeteoS4LGYf9e_wDFGo65PpU1kp0pUMFJHMVROTlZWQ1IwMVlNWTlJWUhaRE83Ty4u" target="_blank" style="font-size: 32px; text-align: right; margin: 20px">
<button class="favorite styled" type="button">
    Register Your Team
</button>
</a>

<!-- REMOVE THIS SECTION when you use this template -->
<div class="lead" markdown="1" style="color: #17479E;">
This hackathon is organized by [Digital Nasional Berhad](https://www.digital-nasional.com.my/),
for DNB Internal Staff.

</div>
<!-- END of section to remove -->
<img src="{{ site.baseurl }}/images/leadingimages.jpg">

<div class="aside" style="color: #17479E">
    <h2><i class="bi bi-calendar3"></i> Event timeline</h2>
    <dl style="font-size: 18px;">
        <dt>{{ site.event_date }}</dt>
        <dd>Hackathon Event Schedule</dd>
        {% if site.registration_status == "soon" or site.registration_status == "open" or site.registration_status == "demo" %}
            <dt>{{ site.registration_opens_date }}</dt>
            <dd>
                Applications open for registration<br>
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

        <dt>{{ site.submission_date }}</dt>
        <dd>Submission Timeline</dd>

        <dt>{{ site.team_semifinal_announcement }}</dt>
        <dd>Announcement of top 10 teams for Jury Pitch Presentation</dd>

        <dt>{{ site.pitch_presentation }}</dt>
        <dd>Jury Pitch Presentation</dd>

        <dt>{{ site.result_date }}</dt>
        <dd>Results Announcement</dd>
    </dl>
</div>


<div class="page-content" aria-label="Content" style="background: white; font-family: 'Open Sans', 'Helvetica Neue', Helvetica, Arial, sans-serif; text-align: justify; text-justify: inter-word; color: #159957;">
<section>
<div class="wrapper">
<div>
<h3> Rules for joining the DNB Hackathon</h3>
<p>1.	All team members have to be on the DNB payroll (permanent or contractor).</p>
<p>2.	Participants can join more than one team if they are willing to. In the case, if a participant is qualified for more than one team in top three, he/she will get only one prize.</p>
<p>3.	When registering a team, team leader must fill the rquired information of the team members in the registration form of DNB Hackathon program along with the selected problem statement.</p>
<p>4.	Teams obtaining first, second or third place only get a prize.</p>
<p>5.	A 5 member Jury (50% external and 50% internal) will decide on the 10 teams having to present for the Jury and the subsequent teams one, two and three.</p>
<p>6.	Your proposed solution must be on slides (Powerpoint) with max of 8 slides (excluding cover slide).</p>
<p>7.	Do make sure that your solution is uploaded before the DNB Hackathon submission deadline; If not, then your solution will be excluded.</p>
</div>
<br>
<div>
<h3>Problem Statements</h3>
Detailed list of problems statemens can be found in <a href="{{ site.baseurl }}{% link projects.md %}"><b>Problem Statements</b></a>
</div>
<div>
<br>
<h3>Q/A</h3>
For futher queries, you can refer to <a href="{{ site.baseurl }}{% link faq.md %}"><b>FAQ</b></a> page.
</div>
</div>
</section>
</div>

  

<p></p>
<p></p>
<div style="font-size: 32px; text-align: center; margin: 20px">
<p>Create your team up to a maximum of 4 members right now and</p>
<p><b>stand a chance to win amazing prizes!</b></p>


<a href="https://forms.office.com/Pages/ResponsePage.aspx?id=VUIF41YjAU2H6BEeteoS4LGYf9e_wDFGo65PpU1kp0pUMFJHMVROTlZWQ1IwMVlNWTlJWUhaRE83Ty4u" target="_blank">
<button class="favorite styled" type="button">
    Register Your Team
</button>
</a>
</div>

<!--[Submit your Work Here](https://digitalnasionalberhad-my.sharepoint.com/:f:/g/personal/mani_kagita_digital-nasional_com_my/ElranH5gA49Fk5Nll3-EL-cB9lGyHqo-Ln38v08fA2xwOg){:.btn target="_blank"}
-->
 


  
<div class="page-content" aria-label="Content" style="background: white; font-family: 'Open Sans', 'Helvetica Neue', Helvetica, Arial, sans-serif; color: #159957;">
<section>
<div class="wrapper">
<h3> Prizes for Top 3 Teams</h3>
<u2 class="grid">

<li class="imag" markdown="1" style="text-align: center">
{% include imagedisplay.html title="First Prize" image="first.png" %}

<p><b>Samsung Galaxy A73 5G</b></p>
<p>(RRP: RM 2099)</p>
</li>

<li class="imag" markdown="1" style="text-align: center">
{% include imagedisplay.html title="Second Prize" image="second.png" %}

<p><b>Realme Pad X</b></p>
<p>(RRP: RM 1699)</p>
</li>

<li class="imag" markdown="1" style="text-align: center">
{% include imagedisplay.html title="Third Prize" image="third.png" %}

<p><b>Samsung Galaxy A23 5G</b></p>
<p>(RRP: RM 999)</p>
</li>

</u2>

</div>
</section>
</div>

