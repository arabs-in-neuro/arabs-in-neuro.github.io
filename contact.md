---
layout: page
title: Contact Us
permalink: /contact
nav: true
---

<html>
  <head>


  </head>
  <body>
  <p id="thanks"></p>

  <div class="publications">
    <script>
    if (window.location.href.length > 47) {
    document.getElementById("thanks").innerHTML =
    "<span style='color: red;'>Thank you for contacting us. We will respond as soon as possible!</span>";
    }
    </script>
    <script type="text/javascript">var submitted=false;</script>
    <iframe name="hidden_iframe" id="hidden_iframe" style="display:none;"
    onload="if(submitted) {window.location='?submitted=true';}"></iframe>

    <form id="contactform" action="https://docs.google.com/forms/d/e/1FAIpQLSdF6btSqvrYiskbvssC3O74JIVhe-hpbyALAcNN9sf2eZRjCA/formResponse" method="post"  target="hidden_iframe" onsubmit="submitted=true;">
          <div class="grid">
          <div class="cell cell--2"><label for="name">Name*</label></div>
          <div class="cell cell--auto"><input type="text" class="form-control" id="name" placeholder="Name*"  name="entry.435430897" required></div>
          </div>

          <div class="form-group">
          <label for="email">Email Address*</label>
          <input type="email"  class="form-control" id="email" placeholder="Email address*" name="entry.86580912" required>
          </div>

          <div class="form-group">
          <label for="subject">Subject*</label>
          <input type="text" class="form-control" id="subject" placeholder="Subject*" name="entry.1456137451">
          </div>

          <div class="form-group">
          <label for="message">Message*</label>
          <textarea rows="5" class="form-control" id="message" placeholder="Message*" name="entry.1141301720" required></textarea>
          </div>

          <button class="button button--outline-primary" type="submit" role="button">Send</button>
    </form>

  </div>

  </body>
</html>
