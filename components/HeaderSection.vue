<template>
      <section class="header">
  <header class="l-header">
    <nav class="nav bd-grid">
      <div>
        <a href="#" class="nav__logo">Muhammad Azhar Firdaus</a>
      </div>

      <div class="nav__menu" id="nav-menu">
        <ul class="nav__list">
          <li class="nav__item"><a href="#home" class="nav__link active-link">Home</a></li>
          <li class="nav__item"><a href="#about" class="nav__link">About</a></li>
          <li class="nav__item"><a href="#skills" class="nav__link">Skills</a></li>
          <li class="nav__item"><a href="#Project" class="nav__link">Project</a></li>
          <li class="nav__item"><a href="#contact" class="nav__link">Contact</a></li>
        </ul>
      </div>

      <div class="nav__toggle" id="nav-toggle">
        <i class='bx bx-menu'></i>
      </div>
    </nav>
  </header>
  </section>
</template>

<script>
export default {
  name: 'HeaderSection'
}





</script>

<style scoped>
.nav__link{
     text-decoration: none; 
}
@import url('/assets/main.css');
</style>
