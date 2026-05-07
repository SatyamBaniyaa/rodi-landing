  <template>
    <v-app>
      <v-main class="bg-black text-white">
        <v-container fluid class="pa-8" style="min-height: 100vh;">



          <v-row align="center" class="mt-16 pt-16">
            <v-col cols="12" md="7">
              <div class="d-flex flex-wrap ga-3 mb-4">
                <v-chip variant="outlined" class="text-uppercase font-weight-bold">
                  ▲ Vercel Solution Partner
                </v-chip>
                <v-chip variant="outlined" class="text-uppercase font-weight-bold">
                  ◆ Netlify Solution Partner
                </v-chip>
                <v-chip variant="outlined" class="text-uppercase font-weight-bold">
                  〰 Tailwind Solution Partner
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
                <v-btn color="white" class="text-black font-weight-black" rounded="lg" size="large">
                  See Available Migrations
                </v-btn>

                <v-btn variant="text" class="text-white font-weight-black" size="large">
                  See Other Services
                </v-btn>
              </div>
            </v-col>

            <v-col cols="12" md="5" class="d-flex justify-center">
              <v-card width="340" height="430" rounded="xl" color="grey-darken-4" class="pa-8 elevation-24">
                <div class="text-uppercase font-weight-black text-yellow-lighten-3 mb-16">
                  Heavy Migration
                </div>

                <div class="text-center mt-16">
                  <p class="text-h6 text-grey font-italic">transform</p>
                  <h2 class="text-h4 font-weight-bold">Next.js pages</h2>

                  <p class="text-h6 text-grey font-italic mt-8">into</p>
                  <h2 class="text-h4 font-weight-bold">Next.js app</h2>
                </div>

                <div class="text-uppercase text-grey mt-16 font-weight-bold">
                  Powered by Candycode
                </div>
              </v-card>
            </v-col>
          </v-row>
        </v-container>
      </v-main>
    </v-app>
  </template>
