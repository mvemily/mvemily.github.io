---
layout: post
title: Donate
description: Donate to Emily's campaign to keep Mountain View a community for all. Every contribution makes a difference!
image: assets/images/about.jpg
nav-menu: false
show_tile: false
---

Donate to Emily's campaign to keep Mountain View a community for all. Every contribution makes a difference!  
  
[Click here to donate online through ActBlue.](https://secure.actblue.com/donate/emilyannramos)

<div class="donation-buttons">

{% for donation in site.data.donation %}
    <a href="https://secure.actblue.com/donate/emilyannramos?amount={{ donation.amount }}" class="button">
        Donate ${{ donation.amount }}
    </a>
{% endfor %}

</div>

Or send in a check: Make checks payable to: **Emily Ann Ramos for Council 2024**  
  
Mail it to:  
PO Box 1026  
Mountain View, CA 94042  
  
Please print and mail [this form](/PrintableDonationForm.pdf) with the check.  
  
*Law requires we ask for your employer and occupation for donations $100 or over. If you don't have an employer or are retired, put N/A, and if you are self-employed put "self-employed" in employer and describe your occupation.*  
