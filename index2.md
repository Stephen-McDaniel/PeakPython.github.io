---
layout: base
title: "Peak Python | Expert Python Ibis and Snowflake Consulting"
css:
  - /assets/css/index.css
ext-css:
  - //fonts.googleapis.com/css?family=Roboto:400,700
js:
  - /assets/js/index2.js
---
<style>    #container {
        position: relative;
    }
    
    #tsparticles {
        position: absolute;
        top: 0;
        left: 0;
        bottom: 0;
        right: 0;
        padding: 0;
        margin: 0;
        z-index: 0; /* if you use -1 you have to set to `"window"` the interactivity.detectsOn property */
    }
    
    #your-div {
        position: absolute;
        top: 0;
        left: 0;
        z-index: 1;
    }
    </style>
<div id="header" class="cut1" markdown="1">

<div id="header-inner" markdown="1">

<div id="tsparticles"></div>
<script src="https://cdn.jsdelivr.net/npm/tsparticles-slim@2.0.6/tsparticles.slim.bundle.min.js"></script>
<script type="text/javascript">
const options = {
interactivity: {
  events: {
    onClick: {
      // this handles the mouse click event
      enable: true,
      mode: "push", // this adds particles
    },
    onHover: {
      // this handles the mouse hover event
      enable: true,
      mode: "repulse", // this make particles move away from the mouse
    },
  },
  modes: {
    push: {
      quantity: 7, // number of particles to add
    },
    repulse: {
      distance: 100, // the distance of the particles from the mouse
    },
  },
},
particles: {
  links: {
    enable: true, // this enables links between particles
    opacity: 0.3,
    distance: 200,
  },
  move: {
    enable: true, // this makes particles move
    speed: { min: 0.1, max: 1 }, // this is the speed of the particles
  },
  opacity: {
    value: { min: 0.2, max: 0.8 }, // this sets the opacity of the particles
  },
  size: {
    value: { min: 1, max: 7 }, // this sets the size of the particles
  },
},
};

// tsParticles.load has two parameters, the first one is the id of the container, the second one is an object with the options
tsParticles.load("tsparticles", options);
</script>
# Peak Python {#title}

## Python Ibis and Snowflake Consulting {#subtitle}

#### Led by Data Engineering, Visualization and Data Science Expert Stephen McDaniel {#sub-subtitle}

<a href="/contact" class="actionbtn">
  <span class="far fa-envelope" aria-hidden="true"></span>
  Contact Us
</a>
{: .actionbtn-out :}

</div>

<div id="main-sections">

<div id="services-out" class="page-section cut1">
  <div id="services">
    <div class="section-title">123. What We Offer</div>
    <div id="services-list">
      <div class="service">
        <img class="service-img" alt="Service image" src="/assets/img/scale-flexiple/Complex dashboard.png" />
        <div class="service-text">Building or improving Shiny apps of any complexity</div>
      </div>
      <div class="service">
        <img class="service-img" alt="Service image" src="/assets/img/scale-flexiple/Successful completion of project.png" />
        <div class="service-text">Group workshops and private tutoring</div>
      </div>
      <div id="services-break"></div>
      <div class="service">
        <img class="service-img" alt="Service image" src="/assets/img/scale-flexiple/Bug tracking.png" />
        <div class="service-text">Code review and optimization of Shiny apps and workflows</div>
      </div>
      <div class="service">
        <img class="service-img" alt="Service image" src="/assets/img/scale-flexiple/Work risk-free.png" />
        <div class="service-text">Professional quality R packages and custom solutions</div>
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
      AttaliTech was launched in 2016 as the world's <b>first</b> Shiny consulting firm. The goal was simple: provide a one-stop shop for any and all of your Shiny needs, while adhering to the <b>highest standards</b>. Today, AttaliTech is a <b>global leader</b> in providing top quality R/Shiny services and is trusted by over 100 companies worldwide. We take pride in knowing you won't get better quality anywhere else.<br/><br/><b>We're certain of it.</b>
    </div>
  </div>
</div>

<div class="cut-buffer values-buffer"></div>

<div id="values-out" class="page-section cut2">
  <div id="values">
	  <div class="section-title">Our Values</div>
    <div id="values-text">
      At AttaliTech, we care about good code, good user experience, and doing things <b>right</b>.<br/><br/>
      We believe in developing every project as if it's your own, <b>never </b>compromising on code quality or end-user experience. We focus on more than just delivering a final product - we're always looking for ways to add more <b>value</b> to our clients. Our clients enjoy peace of mind knowing they can trust us to deliver clean, robust, maintainable code that just works.
    </div>
    <a href="/contact" class="actionbtn">
      Work With Us
    </a>
  </div>
</div>

<div id="clients-out" class="page-section cut1">
  <div id="clients">
    <div class="section-title">Clients</div>
    <div id="clients-subtitle">Clients range from startups to universities to Fortune 500 companies</div>
    <div id="client-logos">
      {% for client in site.data.clients %}
        <a class="client-img" href="{{ client.url }}" title="{{ client.name }}">
          <img alt="{{ client.name }}" src="/assets/img/logos/{{ client.img }}" />
        </a>
      {% endfor %}
    </div>
  </div>
</div>

<div class="cut-buffer"></div>

<div id="aboutme-section-out" class="page-section grey-section cut2">
  <div id="aboutme-section">
    <div class="section-title">About the Founder</div>
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
      Open-Sourced Shiny Apps
    </div>
    <div id="shinyapps-big">
      {% for app in site.data.portfolio %}
	    <div class="shinyapp">
          <a class="applink" href="{{ app.url }}">
            <img class="appimg" src="/assets/img/screenshots/{{ app.img }}" />
            <div class="apptitle">{{ app.title }}</div>
            <div class="appdesc">{{ app.description }}</div>
          </a>
        </div>
	  {% endfor %}
    </div>
  </div>
</div>

<div id="cta-out" class="page-section">
  <div id="cta">
    <div class="section-title">Take Your Shiny Apps to the Highest Level</div><br/>
  </div>
  <a href="/contact" class="actionbtn">
    <span class="far fa-envelope" aria-hidden="true"></span>
    Contact Us
  </a>
</div>

</div>
