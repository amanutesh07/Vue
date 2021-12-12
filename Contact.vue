<template>
  <section id="contact">
    <div class="row section-head">
      <div class="two columns header-col">
        <h1><span>Get In Touch.</span></h1>
      </div>
      <div class="ten columns">
        <p class="lead">If you want to contact us, please use the contact form on this page.
        </p>
      </div>

    </div>

    <div class="row">

      <div style="margin-left: 130px;" class="eight columns">
        <form action="" method="post" id="contactForm" name="contactForm">
          <fieldset>

            <div>
              <label for="contactName">Name <span class="required">*</span></label>
              <input type="text" value="" size="35" id="contactName" name="contactName">
            </div>

            <div>
              <label for="contactEmail">Email <span class="required">*</span></label>
              <input type="text" value="" size="35" id="contactEmail" name="contactEmail">
            </div>

            <div>
              <label for="contactSubject">Subject</label>
              <input type="text" value="" size="35" id="contactSubject" name="contactSubject">
            </div>

            <div>
              <label for="contactMessage">Message <span class="required">*</span></label>
              <textarea cols="50" rows="15" id="contactMessage" name="contactMessage"></textarea>
            </div>

            <div style="margin-left: 180px;">
              <button class="submit">Submit</button>
            </div>

          </fieldset>
        </form>


      </div>

    </div>

  </section>
</template>

<script>
export default {
  name: "Contact"
}
</script>

<style scoped>

</style>