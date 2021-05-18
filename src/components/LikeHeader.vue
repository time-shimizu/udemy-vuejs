<template>
  <div>
    <slot name='title'></slot>
    <p>いいね数</p>
    <slot name='number'></slot>
  </div>
</template>

<script>
export default {
  props: ["headerText"]
};
</script>