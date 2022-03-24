<template>
  <v-app>
    <v-app-bar
      app
      color="red"
      dark
    >

        <div>
        <v-col>
        <h1 class="font-weight-bold">
          E-Learning
        </h1>
        </v-col>
      </div>

      <v-spacer></v-spacer>

      <v-btn
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
        text
      >
        <span class="mr-2">Beranda</span>
        </v-btn>

    <v-btn
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
        text
      >
        <span class="mr-2">Kelas</span>
        </v-btn>
    
    <v-btn
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
        text
      >
        <span class="mr-2">Kelasku</span>
        </v-btn>
      
    <v-spacer></v-spacer>
        
        <v-btn
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
        text
      >
        <span class="mr-2">Login/Register</span>
      </v-btn>
    </v-app-bar>

    <v-main>

      <br />
      <br />
      <br />
      <br />
      <br />
      <br />
        <span>
        <v-col>
        <h1 class="display-1 font-weight-bold mb-3 text-center">
          MEMPERMUDAH KAMU
          <br />
          DALAM BELAJAR!
        </h1>
        </v-col>
        <v-col>
        <h1 class="display-1 font-weight-regular mb-3 text-center">
          Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet
            sint. Velit officia consequat duis enim velit mollit. Exercitation
            veniam.
        </h1>
        </v-col>
          </span>

      
<div class="text-center">
        <v-btn layout="align-center justify-center"
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
        text
      >
        <span class="mr-2">CARI KELASMU SEKARANG!</span>
        </v-btn>
        </div>

        <br />
      <br />
      <br />
      <br />

          

        <v-col>
        <h1 class="display-1 font-weight-bold mb-3 pl-10 text-left">
        SIMPLE
          <br />
        </h1>
        </v-col>
        <v-col>
        <h1 class="display-1 font-weight-regular mb-3 pl-10 text-left">
          Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet
            sint. Velit officia consequat duis enim velit mollit. Exercitation
            veniam.
        </h1>
        
        </v-col>
<br />
      <br />
        <v-col>
        <h1 class="display-1 font-weight-bold mb-3 pr-10 text-right"
        style="margin-right=100">
        CEPAT
        </h1>
        </v-col>

        <v-col>
        <h1 class="display-1 font-weight-regular mb-3 pr-10 text-right">
          Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet
            sint. Velit officia consequat duis enim velit mollit. Exercitation
            veniam.
        </h1>
        </v-col>
    </v-main>
  
  <v-footer
color="red"
    padless
  >
    <v-row
      justify="center"
      no-gutters
    >
      <v-col
        class="light-2 py-4 text-center white--text"
        cols="12"
      >
        {{ new Date().getFullYear() }} — <strong>Ahmad Azhar Agung Furqon</strong>
      </v-col>
    </v-row>
</v-footer>
</v-app>
</template>

<script>

export default {
}
</script>