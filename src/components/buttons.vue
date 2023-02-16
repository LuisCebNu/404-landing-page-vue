<template>
  <div>
    <button class="btn" :style="{ background: color, color: textColor }">
      {{ text }}
    </button>
  </div>
</template>

<script>
export default {
  name: "Button",
  props: {
    text: String,
    color: String,
    textColor: String,
  },
};
</script>