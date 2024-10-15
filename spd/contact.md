---
layout: spd
title: Contact
---

# Contact Developer

Use this form to send an email to the developer.

<form action="https://getform.io/f/02a3564b-9d9e-4cce-8692-50d97bf3c7de" method="POST" enctype="multipart/form-data">
  <label><b>Email Address</b></label><br/>
  <input type="email" name="email" minlength="8" maxlength="256" placeholder="Enter your email"
    oninvalid="this.setCustomValidity('Please enter a valid email')"
    oninput="this.setCustomValidity('')" required>
  <br/>

  <label><b>Name</b></label><br/>
  <input type="text" name="name" minlength="4" maxlength="64" placeholder="Enter your name"
    oninvalid="this.setCustomValidity('Please enter your name')"
    oninput="this.setCustomValidity('')" required>
  <br/>

  <label><b>Reason For Email</b></label><br/>
  <select name="reason" required>
    <option selected disabled value ="">Choose an option</option>
    <option>Contact author</option>
    <option>Question about game</option>
    <option>Report a problem or need help</option>
  </select><br/>

  <label><b>Message</b></label><br/>
  <textarea type="text" name="message" minlength="8" maxlength="2048" placeholder="Enter your message"
    rows="5" style="width:100%; resize:none"
    oninvalid="this.setCustomValidity('Please enter your message to the developer')"
    oninput="this.setCustomValidity('')" required></textarea><br/>

  <label><b>Optional Attachment</b></label><br/>
  <input type="file" name="file"><br/>

  <!-- add hidden Honeypot input to prevent spams -->
  <input type="hidden" name="_gotcha" style="display:none !important"><br/>

  <label><b>Required Captcha</b></label><br/>
  <div class="g-recaptcha" data-sitekey="6LdQdgMkAAAAAKp02EkfqWlezYA_LcdE31DISsiF"></div>

  <br/>
  <button type="submit">Send Email</button>
</form>

<br/>
