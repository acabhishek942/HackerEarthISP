<template>
  <header>
    <div class="headline">
      <h1>{{ title }}</h1>
      <p> - {{ tagline }}</p>
  </div>
  </header>
</template>

<script>
export default {
  data () {
    return {
      title: 'ISP HackerEarth',
      tagline: 'searching ISP made easy!'
    }
  },
  methods:{
  },
}
</script>

<style scoped>
header {
  padding: 10px;
  position: fixed;
  top: 0;
  width: 100%;
  text-align: center;
  display: inline;
}
h1, p {
  color: #278e43;
  text-align: center;
}
.headline h1, .headline p {
  display:inline;
}
</style>
