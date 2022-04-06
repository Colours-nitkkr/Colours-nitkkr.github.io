---
layout: base
title: "KAIR"
css:
  - /assets/css/index.css
ext-css:
  - //fonts.googleapis.com/css?family=Roboto:400,700
js:
  - /assets/js/index.js
ext-js:
  - //cdn.jsdelivr.net/npm/particles.js@2.0.0/particles.min.js
---

<div id="header" class="cut1" markdown="1">

<div id="header-inner" markdown="1">

#        KAIR {#title}

## Exploring The World Humanly {#subtitle}

<a href="/contact" class="actionbtn">
  <span class="far fa-envelope" aria-hidden="true"></span>
  Contact Us
</a>
{: .actionbtn-out :}

</div>


</div>

<div id="main-sections">

<div id="services-out" class="page-section cut1">
  <div id="services">
    <div class="section-title">What We Do</div>
    <div id="services-list">
      <div class="service">
        <img class="service-img" alt="Service image" src="/assets/img/scale-flexiple/Q1.png" />
        <div class="service-text">Computer Vision </div>
      </div>
      <div class="service">
        <img class="service-img" alt="Service image" src="/assets/img/scale-flexiple/Q2.png" />
        <div class="service-text">Reinforcement Learning</div>
      </div>
      <div id="services-break"></div>
      <div class="service">
        <img class="service-img" alt="Service image" src="/assets/img/scale-flexiple/Q3.png" />
        <div class="service-text">Natural Language Processing</div>
      </div>
      <div class="service">
        <img class="service-img" alt="Service image" src="/assets/img/scale-flexiple/Q4.png" />
        <div class="service-text">Data Science/Machine Learning</div>
      </div>
    </div>

    <a href="/contact" class="actionbtn">
      <span class="far fa-envelope" aria-hidden="true"></span>
      Contact Us
    </a>
  </div>
</div>

<div class="cut-buffer aboutus-buffer"></div>

<div id="aboutus-out" class="page-section grey-section cut2">
  <div id="aboutus">
    <div class="section-title">About Us</div>
    <div id="aboutus-text">
    We're a group of <b>passionate and innovation driven individuals</b> who like to solve problems using the power of <b>AI.</b> We want to be a part of the next technological revolution through AI as well as empower more and more people with it. 
    </div>
  </div>
</div>

<div class="cut-buffer values-buffer"></div>

<div id="values-out" class="page-section cut2">
  <div id="values">
	  <div class="section-title">Our Values</div>
    <div id="values-text">
      At KAIR, we care about good code, great learning experience, and doing things the way they should be.<br/><br/>
      The challenges the world is facing today are enormous. These
      issues can be inevitably addressed with the help of AI, which is a huge part
      of the next technological revolution. We believe that there's a need to 
      promote the AI culture in colleges to make people aware of the ongoing trend in the field of tech, so that they can 
      contribute in solving real world problems. <b>We are the first ever AI Research Club of NIT, Kurukshetra!</b>
    </div>
    <a href="/contact" class="actionbtn">
      Work With Us
    </a>
  </div>
</div>

<div class="cut-buffer"></div>

<div id="aboutme-section-out" class="page-section grey-section cut2">
  <div id="aboutme-section">
    <div class="section-title">Research Groups</div>
	<div id="aboutme-list" markdown="1">
{% for info in site.data.main_info %}
{% if info.icon %}<span class="about-icon fa-fw {{ info.icon }}" aria-hidden="true"></span>{% endif info.icon %}
<span class="about-content">{{ info.content }}</span>
{: .about-text }
{% endfor %}
</div>
  </div>
</div>

<div class="cut-buffer portfolio-buffer"></div>

<div id="portfolio-out" class="page-section grey-section">
  <div id="portfolio">
    <div class="section-title">
      Open-Sourced Projects
    </div>
    <div id="shinyapps-big">
      {% for app in site.data.portfolio %}
	    <div class="shinyapp">
            <img class="appimg" src="/assets/img/screenshots/{{ app.img }}" />
            <div class="apptitle">{{ app.title }}</div>
            <div class="appdesc">{{ app.description }}</div>
        </div>
	  {% endfor %}
    </div>
  </div>
</div>

<div id="cta-out" class="page-section">
  <div id="cta">
    <div class="section-title"><span>Have influential ideas?</br>Collaborate with us.</span></div><br/>
  </div>
  <a href="/contact" class="actionbtn">
    <span class="far fa-envelope" aria-hidden="true"></span>
    Contact Us
  </a>
</div>

</div>

