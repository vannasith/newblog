<template>
  <v-container class="pa-0">
    <base-subheading>Tags</base-subheading>

    <v-btn
      v-for="(category, i) in categories"
      :key="i"
      class="mr-2"
      color="secondary"
      label
      small
      tag
      text-color="white"
    >
      {{ category.text }}
    </v-btn>
  </v-container>
</template>

<script>
  // Utilities
  import { mapGetters } from 'vuex'

  export default {
    name: 'Tags',

    computed: {
      ...mapGetters(['categories']),
      
    },
    
  }
</script>
