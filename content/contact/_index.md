+++
type = "page"
page = "contact/contact.html"
title = "Contact"
description = "Eric Thayer is a Web Designer and Front-end Developer from Denver Colorado"
+++

<!-- Contact -->
<section id="contact" class="pt-pb-2">
  <div class="container align-center hidden">
      <p class="sub-header mb-3 mw-35em md-pr-pl-2">Please fill out the contact form or feel free to send me an email.</p>
  </div>
  <div class="container-fluid">
    <!-- Contact Form -->
    <form class="contact-form" name="contact" netlify-honeypot="bot-field" action="../thank-you/" netlify>
      <!-- Form Build -->
      <div class="form-wrap flex flex-wrap">
        <!-- Form Group (left) -->
        <div class="form-group form-group-left flex flex-wrap">
          <!-- Name -->
          <div class="input-row">
            <label class="flex" for="Name">Name <span class="req-mark ml-a text-sm-r"><span aria-hidden="true">*</span> required</span></label>
            <input id="Name" name="Name" type="text" class="required" title="This is a required field" required>
          </div>
          <!-- Email Address -->
          <div class="input-row">
            <label class="flex" for="Email">Email <span class="req-mark ml-a text-sm-r"><span aria-hidden="true">*</span> required</span></label>
            <input id="Email" name="Email" type="email" class="required" title="This is a required field" required>
          </div>
          <!-- Phone Number -->
          <div class="input-row">
            <label for="Phone">Phone</label>
            <input id="Phone" name="Phone" type="tel" title="your best contact phone number">
          </div>
        </div>
        <!-- Form Group (right) -->
        <div class="form-group form-group-right flex flex-wrap">
          <!-- Message Detail -->
          <div class="input-row">
            <label for="Message">Message</label>
            <textarea id="Message" name="Message" title="leave me a message if you want"></textarea>
          </div>
        </div>
        <p class="sr-only hidden">
          <label>Don’t fill this out: <input name="bot-field"></label>
        </p>
        <!-- Submit -->
        <div class="submit-input text-md pt-sm md-pt-1">
          <button class="submit-button" type="submit" tabindex="0"><span>Send</span></button>
        </div>
      </div>
    </form>
  </div>
</section>

