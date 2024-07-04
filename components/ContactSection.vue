<template>
  <section class="contact" id="contact">
    <h2 class="section-title">Contact</h2>
    <h2 class="contact__subtitle">Social Media</h2>
    <p class="contact__text">
      I am active on multiple social media platforms and welcome any business
      inquiries.
    </p>
    <!-- ICON -->
    <div class="contact__social">
      <a
        href="https://www.facebook.com/your-profile"
        target="_blank"
        class="contact__social-icon"
      >
        <img src="~/assets/img/facebook.png" alt="Facebook" />
      </a>

<a href="https://github.com/your-username" target="_blank" class="contact__social-icon">
  <img src="~/assets/img/github.png" alt="GitHub" />
</a>

<a href="https://plus.google.com/your-profile" target="_blank" class="contact__social-icon">
  <img src="~/assets/img/google.png" alt="Google" />
</a>

<a href="https://www.instagram.com/your-username" target="_blank" class="contact__social-icon">
  <img src="~/assets/img/instagram.png" alt="Instagram" />
</a>

    </div>

    <h2 class="contact__subtitle">Direct Mail</h2>
    <p class="contact__text">
      Alternatively, you can contact me directly by filling out the form below.
    </p>
    <div class="contact__container bd-grid">
      <form action="" class="contact__form">
        <input type="text" placeholder="Name" class="contact__input" />
        <input type="mail" placeholder="Email" class="contact__input" />
        <textarea
          type="text"
          cols="0"
          rows="10"
          placeholder="..."
          class="contact__input"
        ></textarea>
        <input type="button" value="Send" class="contact__button button" />
      </form>
    </div>
  </section>
</template>

<script>
export default {
  name: "ContactSection",
};
</script>

<style scoped>
.contact {
  padding: 80px 0;
}
</style>
