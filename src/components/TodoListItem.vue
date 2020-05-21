<template>
  <div>
    <ul>
      <li v-for-key="todo in todos">{{ todo }}</li>
    </ul>
  </div>
</template>

<script>
export default {
  props: ["todos"]
};
</script>

<style></style>
