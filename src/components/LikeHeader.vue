<template>
  <div>
    <slot></slot>
    <slot></slot>
  </div>
</template>

<script>
export default {
  props: ["headerText"]
};
</script>