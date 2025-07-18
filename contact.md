---
layout: default
title: Contact
subtitle: Get in touch with the Climate Dynamics Lab
description: Contact details and location for the Climate Dynamics Lab, IIT Delhi.
---


<!-- Main Content -->
<section class="wrapper style1">
  <div class="container">
        <div id="header">
      <div class="inner">
        <header>
          <h1><a href="{{ '/' | relative_url }}" id="logo">{{ Contact }}</a></h1>
          <hr />
          <p>{{ site.subtitle }}</p>
        </header>
      </div>
    <header class="major">
      <h2>We'd love to hear from you</h2>
    </header>

    <div class="row">
      <!-- Contact Form -->
      <div class="col-6 col-12-mobile">
        <section>
          <form method="post" action="#">
            <div class="row">
              <div class="col-6 col-12-mobile">
                <input type="text" name="name" placeholder="Your Name" required />
              </div>
              <div class="col-6 col-12-mobile">
                <input type="email" name="email" placeholder="Your Email" required />
              </div>
            </div>
            <div class="row">
              <div class="col-12">
                <textarea name="message" placeholder="Your Message" rows="6" required></textarea>
              </div>
            </div>
            <div class="row">
              <div class="col-12">
                <button type="submit" class="button">Send Message</button>
              </div>
            </div>
          </form>
        </section>
      </div>

      <!-- Contact Info + Map -->
      <div class="col-6 col-12-mobile">
        <section>
          <header>
            <h3>Visit Us</h3>
          </header>
          <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; border-radius: 8px; box-shadow: 0 4px 10px rgba(0,0,0,0.1);">
            <iframe src="https://maps.google.com/maps?q=IIT%20Delhi&t=&z=15&ie=UTF8&iwloc=&output=embed" allowfullscreen style="position: absolute; top:0; left:0; width:100%; height:100%; border:0;"></iframe>
          </div>
          <address style="margin-top: 1.5em; line-height: 1.6;">
            <strong>Climate Dynamics Lab</strong><br />
            Centre for Atmospheric Sciences<br />
            IIT Delhi, Hauz Khas<br />
            New Delhi – 110016, India<br />
            <strong>Email:</strong> <a href="mailto:climate.lab@cas.iitd.ac.in">climate.lab@cas.iitd.ac.in</a><br />
            <strong>Phone:</strong> +91-11-2659-XXXX
          </address>
        </section>
      </div>
    </div>
  </div>
</section>
