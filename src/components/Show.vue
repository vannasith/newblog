<template>
  <section id="feed">
    <feed> </feed>
  </section>
</template>

<script>
  export default {
    name: 'HomeAbout',

    components: {
      Feed: () => import('@/components/Feed'),
    },
  }
</script>