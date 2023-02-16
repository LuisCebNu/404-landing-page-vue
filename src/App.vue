<template>
  <div>
    <img
      class="background"
      src="@/assets/background.png"
      height="600"
      width="700"
    />
    <landingPage />
    <Text />
  </div>
</template>

<script>
import landingPage from "./components/landingPage.vue";
import Text from "./components/errorText.vue";

export default {
  name: "App",
  components: {
    landingPage,
    Text,
  },
};
</script>

<style>
.background {
  position: absolute;
  z-index: -1;
  opacity: 30%;
}
.btn {
  display: inline-block;
  background: #000;
  color: #fff;
  border: 0.5px solid black;
  padding: 14px 50px;
  margin: 5px;
  border-radius: 15px;
  cursor: pointer;
  text-decoration: none;
  font-size: 15px;
  font-family: inherit;
  box-shadow: 2px 5px gray;
}
.btn:focus {
  outline: none;
}
.btn:active {
  transform: scale(0.98);
}
.btn:hover {
  box-shadow: 0 0 5px green;
}
.btn-block {
  display: block;
  width: 100%;
}
</style>
