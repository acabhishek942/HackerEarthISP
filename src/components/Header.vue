<template>
  <header>
    <a href=""><img class="logo"src=""/></a>
    <p class="heading">{{ title }}</p>
    <p style="color:#4DB388;font-size:25px;margin-top:50px;float:left;">&nbsp &nbsp&nbsp &nbsp -- {{ tagline }}</p>
    <div class="details"  >Total ISP:{{ total_isp }}&nbsp &nbsp |&nbsp &nbsp API hits:{{ api_hits }}</div>
  </header>

</template>
<script>
export default {

  data () {
    return {
      title: 'ISP HackerEarth',
      tagline: 'searching ISP made easy',
      total_isp: 9,
      api_hits: 748,

    }
  },
  methods:{

    }
  }

</script>

<style >
.logo {
    width: 70px;
    height: 70px;
    padding:20px;

    float:left;
}
.heading{
    margin-left: 20px;
    font-family: 'Arial';
    font-size: 50px;
    font-style: normal;
    font-variant: normal;
    color: #4DB388;

    line-height: 26.4px;
    float:left;

}

.details{
    background:#4DB388;
    display: inline-block;
    font-size:20px;
    border: 2px solid black;
    padding-left:25px;
    padding-right:25px;
    padding-bottom:5px;
    padding-top:5px;
    margin-top:45px;
    margin-left:200px;
    border-radius: 10px;
    text-align:center;
    width:auto;
}
header {
  position: fixed;
  top: 0;
  width: 100%;
  text-align: center;
  display: inline;
  border-bottom: 2px solid black;
}
</style>
