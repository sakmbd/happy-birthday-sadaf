<template>
  <v-container>
    <v-row class="text-center">
      <v-col cols="12">
        <video width="100%" controls autoplay>
          <source src="@/assets/video.mp4" type="video/mp4" />
          Your browser does not support the video tag.
        </video>
      </v-col>
    </v-row>
    <v-row class="text-center">
      <v-col cols="12">
        <v-card class="mx-auto" max-width="400">
          <v-img
            class="white--text align-end"
            height="400px"
            src="@/assets/r1.jpg"
          >
            <v-card-title class="pink"
              >Happy Birthday Sadaf Rehman</v-card-title
            >
          </v-img>
        </v-card>
      </v-col>

      <v-col cols="12">
        <v-card class="mx-auto" max-width="400">
          <v-img
            class="white--text align-end"
            height="400x"
            src="@/assets/3.jpg"
          >
          </v-img>

          <v-card-text class="pink darken-1">
            <div class="white--text">
              “On your birthday I wish you success and endless
              happiness!.Wishing you an awesome birthday!”
            </div>
          </v-card-text>
        </v-card>
      </v-col>

      <v-col cols="12">
        <v-card class="mx-auto" max-width="400">
          <div max-height="400">
            <v-carousel hide-delimiters>
              <v-carousel-item
                v-for="(item, i) in items"
                :key="i"
                :src="item.src"
              ></v-carousel-item>
            </v-carousel>
          </div>
        </v-card>
      </v-col>

      <v-col cols="12">
        <v-card class="mx-auto" color="#26c6da" dark max-width="400">
          <v-card-title>
            <v-icon large left>
              mdi-twitter
            </v-icon>
            <span class="title font-weight-light font-weight-bold"
              >Happy Birthday Sadaf</span
            >
          </v-card-title>

          <v-card-text class="headline font-weight-bold">
            "My dearest sister, wish you a very warm and happy birthday. May
            your sweet smile never fade away. I wish you a very happy and sweet
            birthday. Good bless you.”
          </v-card-text>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script lang="ts">
import Vue from "vue";
export default Vue.extend({
  name: "HelloWorld",
  data() {
    return {
      items: [
        {
          src: "img/sadaf (1).jpg"
        },
        {
          src: "img/sadaf (2).jpg"
        },
        {
          src: "img/sadaf (3).jpg"
        },
        {
          src: "img/sadaf (4).jpg"
        },
        {
          src: "img/sadaf (5).jpg"
        },
        {
          src: "img/sadaf (6).jpg"
        },
        {
          src: "img/sadaf (7).jpg"
        },
        {
          src: "img/sadaf (8).jpg"
        },
        {
          src: "img/sadaf (9).jpg"
        },
        {
          src: "img/sadaf (10).jpg"
        },
        {
          src: "img/sadaf (11).jpg"
        },
        {
          src: "img/sadaf (12).jpg"
        },
        {
          src: "img/sadaf (13).jpg"
        },
        {
          src: "img/sadaf (14).jpg"
        },
        {
          src: "img/sadaf (15).jpg"
        }
      ]
    };
  }
});
</script>
