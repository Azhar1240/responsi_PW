<template>
  <section class="contact">
<h2 class="section-title">Contact</h2>
            <h2 class="contact__subtitle">Social Media</h2>
            <p class="contact__text">I am active on multiple social media platforms and welcome any business inquiries.
            </p>
            <!-- ICON -->
            <div class="contact__social">
                <a href="" class="contact__social-icon"><i class='bx bxl-facebook-circle'></i></a>
                <a href="" class="contact__social-icon"><i class='bx bxl-whatsapp'></i></a>
                <a href="" class="contact__social-icon"><i class='bx bxl-instagram'></i></a>
                <a href="" class="contact__social-icon"><i class='bx bxl-google'></i></a>
            </div>

            <h2 class="contact__subtitle">Direct Mail</h2>
            <p class="contact__text">Alternatively, you can contact me directly by filling out the form below.</p>
            <div class="contact__container bd-grid">
                <form action="" class="contact__form">
                    <input type="text" placeholder="Name" class="contact__input">
                    <input type="mail" placeholder="Email" class="contact__input">
                    <textarea type="text" cols="0" rows="10" placeholder="..." class="contact__input"></textarea>
                    <input type="button" value="Send" class="contact__button button">
                </form>
            </div>
  </section>
</template>

<script>
export default {
  name: 'ContactSection'
}
</script>

<style scoped>
.contact {
  padding: 50px 0;
}
@import url('https://cdn.jsdelivr.net/npm/boxicons@2.0.5/css/boxicons.min.css');
</style>
