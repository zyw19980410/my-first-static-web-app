<template>
  <div>
  
    <img :src="require('../static/vue.png')"/>
    <div>Hello {{ value }}</div>
  </div>
  
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      value: "World!"
    };
  }
};
</script>
