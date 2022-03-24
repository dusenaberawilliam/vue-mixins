<template>
  <div>
    <span>
      <button @click="countHandle">Click Me</button>
      <p>to count</p>
      {{ counter }}
    </span>
  </div>
</template>

<script>
import countMixin from "./mixins/countMixin";
export default {
  name: "CountOnClick",
  mixins: [countMixin],
};
</script>

<style>
</style>