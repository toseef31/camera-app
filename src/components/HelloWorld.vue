<template>
  <div>
    <camera
      :resolution="{ width: 670, height: 477 }"
      @paused="paused"
      autoplay
    ></camera>
  </div>
</template>

<script>
import Camera from "simple-vue-camera";
export default {
  components: {
    Camera,
  },

  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
