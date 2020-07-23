<template>
  <base-card dark>
    <v-img
      :src="require('@/assets/articles/networking.jpg')"
      class="grey lighten-2"
      height="400"
      width="100%"
    >
      <v-row
        class="fill-height pa-3"
        align="center"
      >
        <v-col
          cols="12"
          md="7"
          offset-md="5"
        >
          <h1 class="display-3 font-weight-light">
            Yumtech!
          </h1>

          <div class="subheading text-uppercase pl-2 mb-4">
            Solution Create web blog
          </div>

          <v-btn
            color="primary"
            depressed
          >
            About
          </v-btn>
        </v-col>
      </v-row>
    </v-img>
  </base-card>
</template>

<script>
  export default {
    name: 'HomeBanner',
  }
</script>
