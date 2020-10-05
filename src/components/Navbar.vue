<template>
  <div>
    <Button
      text="Home"
      className="btn btn-red text-color-white"
      type="button"
    />
    <Button
      text="Profile"
      className="btn btn-green text-color-white"
      type="button"
    />
    <Button
      text="Subscriptions"
      className="btn btn-blue text-color-white"
      type="button"
    />
    <Button
      text="Log In"
      className="btn btn-gold text-color-black"
      type="button"
      disabled="true"
    />
    <br /><br />
  </div>
</template>

<script>
import Button from "./Button";

export default {
  components: {
    Button,
  },
  inheritAttrs: false,
};
</script>

