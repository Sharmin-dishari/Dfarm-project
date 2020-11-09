<template>
  <div class="rounded-btn">
    <img :src="image" />
    <span class="button-text">{{image}}</span>
  </div>
</template>

<script>
export default {
  props: {
    image: { type: String },
    text: { tpye: String },
  },
};
</script>

<style scoped>
.rounded-btn {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 200px;
  height: 200px;
  overflow: hidden;
  border-radius: 50%;
  position: relative;
}
.button-text {
  position: absolute;
  bottom: 10px;
}
</style>