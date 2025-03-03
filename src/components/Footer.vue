<template>
  <div class="footer">
    
    <div class="left"><a href="https://github.com/schouffy/gamedev-portfolio" target="blank">Portfolio</a> by schouffy</div>
    <div class="right">Reach me at <a href="mailto:cddatkins@email.com">cddatkins@email.com</a> or <router-link to="/contact">through here</router-link></div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "Footer"
});
</script>

<style scoped lang="less">

@import '../css/variables.less';

.footer {
  background-color: @bodyBgColor;
  width: 100%;
  margin: 20px 0 auto;
  height: 60px;
  font-size: 0.8em;
  opacity: 0.7;
  padding-bottom: 30px;
  position: fixed;
  bottom: 0;
}

.left, .right {
    padding-top: 10px;
    text-align: center;
  }

@media only screen and (min-width: 620px){

  .footer {
    padding: 0;
  }

  .left, .right {
    padding: 20px;
  }

  .left {
    float: left;
  }

  .right {
    float:right;
  }
}
</style>