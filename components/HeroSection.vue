<template>
  <link
    rel="stylesheet"
    href="https://cdn.jsdelivr.net/npm/bootstrap@4.4.1/dist/css/bootstrap.min.css"
  />
  <section class="hero">
    
      <!-- ADDITIONAL -->
            <div class="home__data">
                <h1 class="home__title">Welcome,<br>To My <span class="home__title-color">Portofolio</span><br></h1>
                
                <a href="#" class="button"></a>
            </div>
            
            <div class="home__social">
              
                <a href="" class="home__social-icon"><i class='bx bxl-linkedin'></i></a>
                <a href="" class="home__social-icon"><i class='bx bxl-behance'></i></a>
                <a href="" class="home__social-icon"><i class='bx bxl-github'></i></a>
            </div>
            
            <!-- ORIGINAL -->
  </section>
</template>

<script>
export default {
  name: "HeroSection",
};
</script>

<style scoped>
.hero {
  text-align: center;
  padding: 100px 0;

  margin: 0;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  
}

.button {
  display: inline-block;
  background-color: var(--first-color);
  color: #fff;
  padding: 0.75rem 2.5rem;
  font-weight: var(--font-semi);
  border-radius: 0.5rem;
  transition: 0.3s;
  text-decoration: none;
}
.button:hover {
  box-shadow: 0px 10px 36px rgba(0, 0, 0, 0.15);
}
</style>
