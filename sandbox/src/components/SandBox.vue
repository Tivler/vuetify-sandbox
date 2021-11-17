<template>
  <div class="d-flex justify-space-around">
    <v-card
      class="my-12"
      max-width="374"
    >
      <template slot="progress">
        <v-progress-linear
          color="deep-purple"
          height="10"
          indeterminate
        ></v-progress-linear>
      </template>

      <v-img
        height="350"
        src="https://m.media-amazon.com/images/M/MV5BYTgzNzI0YjctNDQ3My00MGQ4LThhMDEtYWFiZDU3YmExMTEwXkEyXkFqcGdeQXVyNTgyNTA4MjM@._V1_.jpg"
        aspeect-ratio="2"
        position="top top"
      ></v-img>

      <v-card-title>Naruto Uzumaki</v-card-title>

      <v-card-text>
        <v-row
          align="center"
          class="mx-0"
        >
          <v-rating
            :value="5"
            color="amber"
            dense
            half-increments
            readonly
            size="14"
          ></v-rating>

          <div class="grey--text ms-4">
            5 (413)
          </div>
        </v-row>

        <div class="my-4 text-subtitle-1">
        Hokage, Hidden Leaf Village
        </div>

        <div>"I won't run away anymore... I won't go back on my word... that is my ninja way! "To become Hokage is my dream!"</div>
      </v-card-text>
    </v-card>

    <v-card
      class="my-12"
      max-width="374"
    >
      <template slot="progress">
        <v-progress-linear
          color="deep-purple"
          height="10"
          indeterminate
        ></v-progress-linear>
      </template>

      <v-img
        height="350"
        src="https://wallpaperaccess.com/full/4306732.jpg"
        aspeect-ratio="2"
        position="right"
      ></v-img>

      <v-card-title>Sasuke Uchiha</v-card-title>

      <v-card-text>
        <v-row
          align="center"
          class="mx-0"
        >
          <v-rating
            :value="3"
            color="amber"
            dense
            half-increments
            readonly
            size="14"
          ></v-rating>

          <div class="grey--text ms-4">
            3 (123)
          </div>
        </v-row>

        <div class="my-4 text-subtitle-1">
        Ninja, Hidden Leaf Village
        </div>

        <div>"This is the path I walk on. Not you or anyone can change that."</div>
      </v-card-text>
    </v-card>

    <v-card
      class="my-12"
      max-width="374"
    >
      <template slot="progress">
        <v-progress-linear
          color="deep-purple"
          height="10"
          indeterminate
        ></v-progress-linear>
      </template>

      <v-img
        height="350"
        src="https://media.distractify.com/brand-img/vQClzyLLl/0x0/itachi-featured-1632854701914.png"
        aspeect-ratio="2"
        position="center center"
      ></v-img>

      <v-card-title>Itachi Uchiha</v-card-title>

      <v-card-text>
        <v-row
          align="center"
          class="mx-0"
        >
          <v-rating
            :value="4"
            color="amber"
            dense
            half-increments
            readonly
            size="14"
          ></v-rating>

          <div class="grey--text ms-4">
            5 (413)
          </div>
        </v-row>

        <div class="my-4 text-subtitle-1">
        Rogue Ninja, Hidden Leaf Village
        </div>

        <div>“If you want to know who you are, you have to look at your real self and acknowledge what you see.”</div>
      </v-card-text>
    </v-card>
  </div>
</template>

<script>
  export default {
    name: 'SandBox',
  }
</script>

<style scoped>
  
</style>
