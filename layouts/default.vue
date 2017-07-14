<style lang="scss">
  #default-layout {

    main {
      position: relative;
      top: 8rem;
    }

  }
</style>

<template>
  <div id="default-layout">
    <navbar/>
    <main>
      <nuxt/>
    </main>
  </div>
</template>

<script>
  import Navbar from '~components/Navbar'

  export default {
    components: {
      Navbar
    }
  }
</script>
