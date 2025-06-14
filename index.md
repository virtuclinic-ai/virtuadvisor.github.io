---
layout: default
title: VirtuClinic
use_math: true
lang: zh
comments: true
---
{% include JB/setup %}
<div class="page-header">
  <div class="pull-right">
    {% include contact_icons %}
  </div>
  <h1>
    Hi, Welcome!
    {% if site.tagline %}<br/><small>{{ site.tagline }}</small>{% endif %}
  </h1>
</div>

<style>
  body {
    font-family: Arial, sans-serif;
    background-color: #f9f9f9;
    color: #333;
  }

  header {
    background-color: #001f3f;
    padding: 1rem;
    text-align: center;
  }

  header img {
    height: 50px;
  }

  main {
    max-width: 800px;
    margin: 2rem auto;
    padding: 2rem;
    background-color: #fff;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
  }

  h1, h2, h3 {
    color: #001f3f;
  }

  p, li {
    line-height: 1.6;
  }

  .center {
    display: block;
    margin: 1rem auto;
    border-radius: 8px;
    width: 100%;
    max-width: 300px;
  }

  .contact-form {
    display: flex;
    flex-direction: column;
    gap: 0.5rem;
    margin-top: 1rem;
  }

  .contact-form input, .contact-form textarea {
    padding: 0.5rem;
    border: 1px solid #ccc;
    border-radius: 4px;
    width: 100%;
  }

  .contact-form button {
    background-color: #001f3f;
    color: #fff;
    padding: 0.75rem;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    transition: background-color 0.3s;
  }

  .contact-form button:hover {
    background-color: #003366;
  }

  footer {
    text-align: center;
    margin: 2rem 0;
  }

  .social-links a {
    margin: 0 0.5rem;
    color: #001f3f;
    text-decoration: none;
    font-size: 1.2rem;
  }

  .social-links a:hover {
    color: #ff4136;
  }
</style>

<header>
  <img src="images/main/virtu-logo.png" alt="VirtuClinic Logo">
</header>
<div align="center">
<p>VirtuClinic's Digital Health Advisor provides 24/7 access to trusted, reliable health information for a personalized healthcare experience—reducing costs, improving productivity, and supporting physical and mental health.</p>
<p>Our expert clinicians and technology deliver health advice and help navigate the health system at any time, day or night.</p>
</div>

<main>
  
  <div align="center">
  <h2>24/7 Triage Providing Trusted Health Support for Your Business</h2>
  </div>  
  <iframe width="100%" height="400" src="https://www.youtube.com/embed/FgG-5-brZSg" frameborder="0" allowfullscreen class="center"></iframe>

   <div style="text-align: center; margin-top: 2rem;">
  <p>Want instant, trusted health support? Visit our Digital Health Advisors page now:</p>
  <a href="archive.html" style="
    display: inline-block;
    background-color: #001f3f;
    color: #fff;
    padding: 0.75rem 1.5rem;
    border-radius: 4px;
    text-decoration: none;
    font-weight: bold;
    transition: background-color 0.3s;">
    Visit Digital Health Advisors
  </a>
</div>


  <h2>Contact Us</h2>
  <form class="contact-form">
    <input type="text" placeholder="Name" required>
    <input type="email" placeholder="Email" required>
    <input type="tel" placeholder="Phone Number">
    <textarea rows="4" placeholder="Message" required></textarea>
    <button type="submit">Contact Us</button>
  </form>

  <div align="center" class="social-links">
    <a href="https://www.instagram.com/virtuclinic.ca/" target="_blank">Instagram</a>
    <a href="https://www.facebook.com/virtuclinic" target="_blank">Facebook</a>
    <a href="https://www.youtube.com/@VirtuClinic" target="_blank">YouTube</a>
  </div>
</main>

<footer>
  &copy; 2025 VirtuClinic. All rights reserved.
</footer>
