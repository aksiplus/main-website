<template>
<!-- Contact Section -->
  <section class="page-section" id="contact" style="background:#fff">
    <div class="container">

      <!-- Contact Section Heading -->
      <h2 class="page-section-heading text-uppercase text-secondary mb-0">Contact Me</h2>
      <hr>

      <!-- Contact Section Form -->
      <div class="row">
        <div class="col-lg-6 mx-auto">
          <!-- To configure the contact form email address, go to mail/contact_me.php and update the email address in the PHP file on line 19. -->
          <form name="sentMessage" id="contactForm" novalidate="novalidate">
            <div class="control-group">
              <div class="form-group floating-label-form-group controls mb-0 pb-2">
                <label>Name</label>
                <input class="form-control" id="name" type="text" placeholder="Name" required="required" data-validation-required-message="Please enter your name.">
                <p class="help-block text-danger"></p>
              </div>
            </div>
            <div class="control-group">
              <div class="form-group floating-label-form-group controls mb-0 pb-2">
                <label>Email Address</label>
                <input class="form-control" id="email" type="email" placeholder="Email Address" required="required" data-validation-required-message="Please enter your email address.">
                <p class="help-block text-danger"></p>
              </div>
            </div>
            <div class="control-group">
              <div class="form-group floating-label-form-group controls mb-0 pb-2">
                <label>Phone Number</label>
                <input class="form-control" id="phone" type="tel" placeholder="Phone Number" required="required" data-validation-required-message="Please enter your phone number.">
                <p class="help-block text-danger"></p>
              </div>
            </div>
            <div class="control-group">
              <div class="form-group floating-label-form-group controls mb-0 pb-2">
                <label>Message</label>
                <textarea class="form-control" id="message" rows="5" placeholder="Message" required="required" data-validation-required-message="Please enter a message."></textarea>
                <p class="help-block text-danger"></p>
              </div>
            </div>
            <br>
            <div id="success"></div>
            <div class="form-group">
              <button type="submit" class="btn btn-primary btn-xl" id="sendMessageButton">Send</button>
            </div>
          </form>
        </div>
        <div class="col-md-6 mx-auto">
          <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d15832.743701385612!2d107.94009!3d-7.219622!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x6ae23a98ee614243!2sAKSi%2B!5e0!3m2!1sen!2sid!4v1558804334394!5m2!1sen!2sid" width="100%" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>
        </div>
      </div>

    </div>
  </section>
</template>

<script>
export default {
  layout: 'default'
}
</script>
