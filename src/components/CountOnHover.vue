<template>
  <div>
    <span>
      <button @mouseover="countHandle">Touch Me</button>
      <p>to count</p>
      {{ counter }}
    </span>
  </div>
</template>

<script>
import countMixin from "./mixins/countMixin";
export default {
  name: "CountOnHover",
  mixins: [countMixin],
};
</script>

<style>
</style>