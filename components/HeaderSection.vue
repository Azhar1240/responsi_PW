<template>
  <section class="header">
    <header class="l-header">
      <nav class="nav bd-grid">
        <div>
          <a href="#" class="nav__logo">Muhammad Azhar Firdaus</a>
        </div>

        <div class="nav__menu" id="nav-menu">
          <ul class="nav__list">
            <li class="nav__item">
              <a href="#" class="nav__link active-link">Home</a>
            </li>
            <li class="nav__item">
              <a href="#about" class="nav__link">About</a>
            </li>
            <li class="nav__item">
              <a href="#Skills" class="nav__link">Skills</a>
            </li>
            <li class="nav__item">
              <a href="#projects" class="nav__link">Project</a>
            </li>
            <li class="nav__item">
              <a href="#contact" class="nav__link">Contact</a>
            </li>
          </ul>
        </div>

        <div class="nav__toggle" id="nav-toggle">
          <i class="bx bx-menu"></i>
        </div>
      </nav>
    </header>
  </section>
</template>

<style scoped>
.nav__link {
  text-decoration: none;
  position: relative;
  color: #030202;
}

.nav__link:hover {
  position: relative;
}

.nav__link:hover::after {
  position: absolute;
  content: "";
  width: 100%;
  height: 0.18rem;
  left: 0;
  top: 2rem;
  background-color: var(--second-color);
}

@import url("/assets/main.css");
</style>
