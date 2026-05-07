  <template>
    <v-app>
      <v-main class="bg-black text-white">
        <v-container fluid class="pa-8" style="min-height: 90%;">



          <v-row align="center" class="mt-4 pt-4">
            <v-col cols="12" md="7">
              <div class=" d-flex flex-wrap ga-1 mb-1">
                <v-chip variant="outlined" size="small" class=" brand text-h1 text-uppercase font-weight-light ">
                  ▲Vercel <span> Solution Partner</span>
                </v-chip>
                <v-chip variant="outlined" class="brand text-lowercase font-weight-light" size="small">
                  ◆ Netlify <span>Solution Partner </span>
                </v-chip>
                <v-chip variant="outlined" class="brand  text-lowecase font-weight-light" size="small">
                  〰 Tailwind <span>Solution Partner</span>
                </v-chip>
              </div>

              <h1 class="text-h1 font-weight-light mb-4" style="line-height: .95;">
                Imagine never dealing<br />
                with an upgrade again
              </h1>

              <p class="text-h6 text-grey-lighten-1 mb-8" style="max-width: 850px;">
                Staying current is critical for user experience, development velocity,
                and security compliance. But you should be focused on what only you can do.
                We love brutal React migrations.
              </p>

              <div class="d-flex align-center ga-6">
                <v-btn color="white" class="text-black font-weight-black text-sm" rounded="lg" size="small">
                  See Available Migrations
                </v-btn>

                <v-btn variant="text" class="text-white font-weight-black text-sm" size="small">
                  See Other Services
                </v-btn>
              </div>
            </v-col>

            <v-col cols="12" md="5" class="d-flex justify-center">
              <v-card width="340" height="430" rounded="xl" color="grey-darken-4" class="pa-8 elevation-24">
                <div class="text-uppercase font-weight-black  mb-16 justify-center" style="
      letter-spacing: 2px;
      background: linear-gradient(to right, #fff, #777);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    ">
                  Heavy Migration
                </div>

                <div class="text-center mt-16">
                  <p class="text-h6 text-grey font-italic">transform</p>
                  <h2 class="text-h4 font-weight-bold">Next.js pages</h2>

                  <p class="text-h6 text-grey font-italic mt-8">into</p>
                  <h2 class="text-h4 font-weight-bold">Next.js app</h2>
                </div>

                <div class="text-uppercase text-grey mt-16 font-weight-bold text-sm">
                  Powered by Rodilabs
                </div>
              </v-card>
            </v-col>
          </v-row>
        </v-container>
      </v-main>
    </v-app>
  </template>

<style scoped>
.brand {
  font-size: small;
  font-weight: 90;

  letter-spacing: 0;
}

.brand span {
  color: #8e949d;
  font-weight: 70;
  font-size: x-small;
  padding: 3px;
}
</style>
