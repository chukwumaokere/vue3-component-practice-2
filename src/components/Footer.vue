<template>
  <div class="footer">{{ text }}</div>
</template>

<script>
export default {
  props: {
    text: String,
  },
};
</script>

<style scoped>
.footer {
  position: fixed;
  left: 0;
  bottom: 0;
  width: 100%;
  background-color: red;
  color: white;
  font-size: 1.2rem;
  text-align: center;
  height: 2rem;
  justify-content: center;
  align-items: center;
}
</style>