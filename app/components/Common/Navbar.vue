<template>
  <v-app-bar flat height="108" color="transparent">
    <v-container fluid class="px-6 px-md-12 px-lg-16">
      <div class="d-flex align-center w-100">
        <a class="brand text-gray text-decoration-none" href="#">
          Rodi<span >Labs</span>
        </a>

        <div class="nav-pill d-none d-md-flex align-center mx-auto pa-1">
          <v-btn color="white" rounded="lg" class="text-none font-weight-black" href="#services">
            Services
          </v-btn>
          <v-btn variant="text" class="text-white text-none font-weight-black" href="#work">
            Work
          </v-btn>
          <v-btn variant="text" class="text-white text-none font-weight-black" href="#contact">
            Contact
          </v-btn>
        </div>

        <v-btn rounded="lg" color="white" size="large"
          class="text-black text-none text-uppercase bg-black font-weight-black" href="#contact">
          <v-icon icon="mdi-magic-staff" size="24" class="mr-2  " />
          Start
        </v-btn>
      </div>
    </v-container>
  </v-app-bar>
</template>

<style scoped>
.brand {
  font-size: clamp(30px, 3vw, 43px);
  font-weight: 950;
  line-height: 1;
  letter-spacing: 0;
}

.brand span {
  color: #0866df;
  font-weight: 700;
}

.nav-pill {
  background: rgba(28, 29, 34, 0.94);
  border: 1px solid rgba(255, 255, 255, 0.08);
  border-radius: 12px;
}
</style>
