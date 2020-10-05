<template>
  <br />
  <form class="example" action="action_page.php">
    <input type="text" :placeholder="placeholder" name="search" />
  </form>
</template>

<script>
export default {
  props: {
    placeholder: String,
  },
  inheritAttrs: false,
};
</script>

<style scoped>
/* Style the search field */
form.example input[type="text"] {
  padding: 10px;
  font-size: 17px;
  border: 1px solid grey;
  border-radius: 8px;
  float: left;
  width: 100%;
  background: #f1f1f1;
}

/* Style the submit button */
form.example button {
  float: left;
  width: 20%;
  padding: 10px;
  background: #2196F3;
  color: white;
  font-size: 17px;
  border: 1px solid grey;
  border-left: none; /* Prevent double borders */
  cursor: pointer;
}

form.example button:hover {
  background: #0b7dda;
}

/* Clear floats */
form.example::after {
  content: "";
  clear: both;
  display: table;
}
</style>