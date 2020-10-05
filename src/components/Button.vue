<template>
  <button :type="type" :class="className" :disabled="disabled">
    {{ text }}
  </button>
</template>

<script setup>
export default {
  props: {
    text: String,
    type: String,
    className: String,
    disabled: Boolean,
  },
  inheritAttrs: false,
};
</script>

<style>
.btn {
  padding: 12px 20px;
  border-radius: 8px;
  font-size: 1.05rem;
  min-width: 120px;
  margin: 5px;
  border-width: 0;
  cursor: pointer;
  transition: opacity 200ms ease-out;
  box-shadow: 1px 1px 1px rgba(0, 0, 0, 0.2);
}
.btn:hover {
  opacity: 0.6;
}
.btn[disabled] {
  opacity: 0.4;
  cursor: disabled;
}
.text-color-white {
  color: white;
}
.text-color-black {
  color: black;
}
.btn-blue {
  background-color: blue;
}
.btn-red {
  background-color: red;
}
.btn-green {
  background-color: green;
}
.btn-gold {
  background-color: gold;
}
</style>
