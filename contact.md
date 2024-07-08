---
layout: page
title: Contact
permalink: /contact/
---

<h2>Contact Me</h2>
<form action="https://formspree.io/f/movaqblp" method="POST" class="contact-form">
  <div class="form-group">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required>
  </div>
  <div class="form-group">
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required>
  </div>
  <div class="form-group">
    <label for="subject">Subject:</label>
    <input type="text" id="subject" name="subject" required>
  </div>
  <div class="form-group">
    <label for="message">Message:</label>
    <textarea id="message" name="message" rows="10" required></textarea>
  </div>
  <div class="form-actions">
    <button type="submit" class="btn btn-primary">Send</button>
    <button type="reset" class="btn btn-secondary">Reset</button>
  </div>
</form>
