<template>
  <section class="skills" id="Skills">
    <h2 class="section-title">Skills</h2>

    <div class="skills__container bd-grid">
      <div>
        <!-- add text -->
        <h2 class="skills__subtitle">Description</h2>
        <p class="skills__text">
          Dalam dunia yang terus berubah ini, saya memadukan keahlian teknis
          yang kuat dengan visi kreatif untuk menghadirkan pengalaman web yang
          menakjubkan. Saya percaya bahwa setiap proyek merupakan kesempatan
          untuk mewujudkan ide-ide dengan menggunakan teknologi terkini. Dengan
          fokus pada pengembangan front-end, saya tidak hanya menciptakan situs
          web yang fungsional, tetapi juga menghadirkan estetika yang menawan
          untuk setiap pengguna.
        </p>
      </div>

      <!-- add img -->
      <div>
        <img src="assets/img/work6.jpg" alt="" class="skills__img" />
      </div>

      <!-- SKILLS 1 -->
      <div>
        <h2 class="skills__subtitle">Project Experiences</h2>
        <!-- Add Skills -->
        <div class="skills__data">
          <div class="skills__names">
            <i class="bx bxl-html5 skills__icon"></i>
            <span class="skills__name">FRONT-END</span>
          </div>
          <div class="skills__bar skills__html"></div>
          <div>
            <span class="skills__percentage">95%</span>
          </div>
        </div>
        <div class="skills__data">
          <div class="skills__names">
            <i class="bx bxl-css3 skills__icon"></i>
            <span class="skills__name">BACK-END</span>
          </div>
          <div class="skills__bar skills__css"></div>
          <div>
            <span class="skills__percentage">85%</span>
          </div>
        </div>
        <div class="skills__data">
          <div class="skills__names">
            <i class="bx bxl-javascript skills__icon"></i>
            <span class="skills__name">Web Designer</span>
          </div>
          <div class="skills__bar skills__js"></div>
          <div>
            <span class="skills__percentage">65%</span>
          </div>
        </div>
        <div class="skills__data">
          <div class="skills__names">
            <i class="bx bxs-paint skills__icon"></i>
            <span class="skills__name">E-commerce Website Development</span>
          </div>
          <div class="skills__bar skills__ux"></div>
          <div>
            <span class="skills__percentage">85%</span>
          </div>
        </div>
      </div>

      <!-- SKILLS 2 -->
      <div>
        <h2 class="skills__subtitle">Professional Skills</h2>
        <!-- Add Skills -->
        <div class="skills__data">
          <div class="skills__names">
            <i class="bx bxl-html5 skills__icon"></i>
            <span class="skills__name">HTML5</span>
          </div>
          <div class="skills__bar skills__html"></div>
          <div>
            <span class="skills__percentage">95%</span>
          </div>
        </div>
        <div class="skills__data">
          <div class="skills__names">
            <i class="bx bxl-css3 skills__icon"></i>
            <span class="skills__name">CSS3</span>
          </div>
          <div class="skills__bar skills__css"></div>
          <div>
            <span class="skills__percentage">85%</span>
          </div>
        </div>
        <div class="skills__data">
          <div class="skills__names">
            <i class="bx bxl-javascript skills__icon"></i>
            <span class="skills__name">JAVASCRIPT</span>
          </div>
          <div class="skills__bar skills__js"></div>
          <div>
            <span class="skills__percentage">65%</span>
          </div>
        </div>
        <div class="skills__data">
          <div class="skills__names">
            <i class="bx bxs-paint skills__icon"></i>
            <span class="skills__name">UX/UI</span>
          </div>
          <div class="skills__bar skills__ux"></div>
          <div>
            <span class="skills__percentage">85%</span>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "SkillsSection",
};
</script>

<style scoped>
.skills {
  padding: 80px 0;
}
</style>
