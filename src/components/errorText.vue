<template>
  <div class="text">
    <p>
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
      tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
      veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
      commodo consequat.
    </p>
  </div>
  <div class="btn-position">
    <Buttons
      style="float: left"
      :text="'Home Page'"
      :color="'green'"
      :textColor="'white'"
    />
    <Buttons
      style="float: left"
      :text="'Get Help'"
      :color="'transparent'"
      :textColor="'black'"
    />
  </div>
</template>

<script>
import Buttons from "./buttons.vue";
export default {
  components: {
    Buttons,
  },
};
</script>

<style scoped>
.text {
  font-size: 110%;
  text-align: justify;
  padding: 0px 70px 20px 60px;
}

.btn-position {
  margin: 1rem;
  padding: 0rem 10rem 10rem;
}
</style>